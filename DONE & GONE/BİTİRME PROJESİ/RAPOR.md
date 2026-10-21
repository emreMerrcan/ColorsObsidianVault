![[Pasted image 20260411174350.png]]

# TODO
- [x] 11 : Şemayı ve zihin haritasını çıkar. Proje günlüğü ve dizayn seçimlerini yaz
- [x] 12 : İlk 7 başlığı yaz
- [x] 13 : 8 ve son başlıkları yaz. Manifacture test results (try to work the model a little for gods sake)
- [ ] 14 : Ünde hocayla görüş ofis satinde, manifacture test results, english version finish (oh god no)
- [ ] 15 : Finalize and send

# Progress Report 1
### Progress Plan
Proje günlüğüne dair toplu girdiler halindeki bir şema yerine, aralıklı raporlar halinde hazırlanacak üç belgeye karar kılındı.

### Project Design
Projenine el tanımlaması üzerindeki yüksek tanıma oranlarına sahip kompleks bir makine olmasındansa, kabul edilebilir seviyelerde, akıcı bir program olması gerekmekteydi.

Tanımlanması gereken el ifadeleri ve çıktılar göz önünde bulundurulduğunda harekete dayalı tanımlamalardan vaz geçilerek static clasificasyon yapma kararı aldım.

Test süreci için kullanıcıların elle kolayca yapabileceği on el ifadesi tasarladım.

İki elin algılanmasının oluşturduğu konbinasyon sayısı ve göreceli hareketleri algılayan algoritmalar potansiyeli. Ayrıca parmak uzaklıkları çıktısı

### Talk about design choices, mediapipe and custom model
Mediapipe ın 

MLP dizayn ve mimarisi

Infrence dizaynı

### Datasets loaded, workplace choices
Kendi biriktirdiğim dataset

Yalnızca el kordinatları ve uç nokta farklatıyla yetinmem

Yüklediğim diğer dataset, keypointleri işlenerek pure datasete çevriliyor ve eğitimde kullanılabiliyor

### Normalization Standards and Choices
Model yalnızca göreceli el noktalarının pozisyonlarına odaklanmalı

Root relative coordinates

Left hand mirroring

In plane rotation using wrist to landmark 9

scale by max xy radius from root


### Examine Test results etc.

Mention these to be a haphazard dataset testing

acuracy f1 confusion matrix etc.

Mention fps and speed


# Çıktı
2026-04-14 12:32:44.573098: I tensorflow/core/util/port.cc:113] oneDNN custom operations are on. You may see slightly different numerical results due to floating-point round-off errors from different computation orders. To turn them off, set the environment variable `TF_ENABLE_ONEDNN_OPTS=0`.
WARNING:tensorflow:From C:\Users\emrek\Desktop\HandGesture\GesturePorject\.venv\lib\site-packages\keras\src\losses.py:2976: The name tf.losses.sparse_softmax_cross_entropy is deprecated. Please use tf.compat.v1.losses.sparse_softmax_cross_entropy instead.

Loaded data: X(1001, 1, 63), y(1001,)
Label remap (original -> class index): {0: 0, 1: 1, 2: 2, 3: 3, 4: 4, 5: 5, 6: 6, 7: 7, 8: 8, 9: 9}
WARNING:tensorflow:From C:\Users\emrek\Desktop\HandGesture\GesturePorject\.venv\lib\site-packages\keras\src\backend.py:1398: The name tf.executing_eagerly_outside_functions is deprecated. Please use tf.compat.v1.executing_eagerly_outside_functions instead.

2026-04-14 12:32:53.567553: I tensorflow/core/platform/cpu_feature_guard.cc:182] This TensorFlow binary is optimized to use available CPU instructions in performance-critical operations.
To enable the following instructions: SSE SSE2 SSE3 SSE4.1 SSE4.2 AVX2 FMA, in other operations, rebuild TensorFlow with the appropriate compiler flags.
Model: "hand_gesture_mlp"
_________________________________________________________________
 Layer (type)                Output Shape              Param #   
=================================================================
 dense (Dense)               (None, 256)               16384     
                                                                 
 batch_normalization (Batch  (None, 256)               1024      
 Normalization)                                                  
                                                                 
 dropout (Dropout)           (None, 256)               0         
                                                                 
 dense_1 (Dense)             (None, 128)               32896     
                                                                 
 batch_normalization_1 (Bat  (None, 128)               512       
 chNormalization)                                                
                                                                 
 dropout_1 (Dropout)         (None, 128)               0         
                                                                 
 dense_2 (Dense)             (None, 64)                8256      
                                                                 
 dropout_2 (Dropout)         (None, 64)                0         
                                                                 
 dense_3 (Dense)             (None, 10)                650       
                                                                 
=================================================================
Total params: 59722 (233.29 KB)
Trainable params: 58954 (230.29 KB)
Non-trainable params: 768 (3.00 KB)
_________________________________________________________________
Epoch 1/80
WARNING:tensorflow:From C:\Users\emrek\Desktop\HandGesture\GesturePorject\.venv\lib\site-packages\keras\src\utils\tf_utils.py:492: The name tf.ragged.RaggedTensorValue is deprecated. Please use tf.compat.v1.ragged.RaggedTensorValue instead.

WARNING:tensorflow:From C:\Users\emrek\Desktop\HandGesture\GesturePorject\.venv\lib\site-packages\keras\src\engine\base_layer_utils.py:384: The name tf.executing_eagerly_outside_functions is deprecated. Please use tf.compat.v1.executing_eagerly_outside_functions instead.

20/20 [==============================] - 2s 11ms/step - loss: 1.9058 - accuracy: 0.3609 - val_loss: 1.8218 - val_accuracy: 0.6375 - lr: 0.0010
Epoch 2/80
20/20 [==============================] - 0s 4ms/step - loss: 0.9870 - accuracy: 0.6609 - val_loss: 1.4411 - val_accuracy: 0.7563 - lr: 0.0010
Epoch 3/80
20/20 [==============================] - 0s 3ms/step - loss: 0.6468 - accuracy: 0.7875 - val_loss: 1.0999 - val_accuracy: 0.8250 - lr: 0.0010
Epoch 4/80
20/20 [==============================] - 0s 3ms/step - loss: 0.5055 - accuracy: 0.8156 - val_loss: 0.8569 - val_accuracy: 0.8375 - lr: 0.0010
Epoch 5/80
20/20 [==============================] - 0s 3ms/step - loss: 0.3940 - accuracy: 0.8750 - val_loss: 0.6555 - val_accuracy: 0.9062 - lr: 0.0010
Epoch 6/80
20/20 [==============================] - 0s 3ms/step - loss: 0.3215 - accuracy: 0.9094 - val_loss: 0.5306 - val_accuracy: 0.9125 - lr: 0.0010
Epoch 7/80
20/20 [==============================] - 0s 3ms/step - loss: 0.2838 - accuracy: 0.9047 - val_loss: 0.4273 - val_accuracy: 0.9312 - lr: 0.0010
Epoch 8/80
20/20 [==============================] - 0s 3ms/step - loss: 0.2313 - accuracy: 0.9375 - val_loss: 0.3419 - val_accuracy: 0.9312 - lr: 0.0010
Epoch 9/80
20/20 [==============================] - 0s 3ms/step - loss: 0.2549 - accuracy: 0.9078 - val_loss: 0.2695 - val_accuracy: 0.9438 - lr: 0.0010
Epoch 10/80
20/20 [==============================] - 0s 3ms/step - loss: 0.1999 - accuracy: 0.9438 - val_loss: 0.2429 - val_accuracy: 0.9438 - lr: 0.0010
Epoch 11/80
20/20 [==============================] - 0s 3ms/step - loss: 0.1746 - accuracy: 0.9500 - val_loss: 0.2032 - val_accuracy: 0.9500 - lr: 0.0010
Epoch 12/80
20/20 [==============================] - 0s 3ms/step - loss: 0.1752 - accuracy: 0.9406 - val_loss: 0.2055 - val_accuracy: 0.9625 - lr: 0.0010
Epoch 13/80
20/20 [==============================] - 0s 3ms/step - loss: 0.1635 - accuracy: 0.9438 - val_loss: 0.1780 - val_accuracy: 0.9375 - lr: 0.0010
Epoch 14/80
20/20 [==============================] - 0s 3ms/step - loss: 0.1626 - accuracy: 0.9422 - val_loss: 0.1782 - val_accuracy: 0.9375 - lr: 0.0010
Epoch 15/80
20/20 [==============================] - 0s 3ms/step - loss: 0.1303 - accuracy: 0.9609 - val_loss: 0.1614 - val_accuracy: 0.9563 - lr: 0.0010
Epoch 16/80
20/20 [==============================] - 0s 3ms/step - loss: 0.1545 - accuracy: 0.9500 - val_loss: 0.1353 - val_accuracy: 0.9688 - lr: 0.0010
Epoch 17/80
20/20 [==============================] - 0s 3ms/step - loss: 0.1127 - accuracy: 0.9609 - val_loss: 0.1538 - val_accuracy: 0.9500 - lr: 0.0010
Epoch 18/80
20/20 [==============================] - 0s 3ms/step - loss: 0.1322 - accuracy: 0.9609 - val_loss: 0.1211 - val_accuracy: 0.9750 - lr: 0.0010
Epoch 19/80
20/20 [==============================] - 0s 3ms/step - loss: 0.1150 - accuracy: 0.9578 - val_loss: 0.1341 - val_accuracy: 0.9563 - lr: 0.0010
Epoch 20/80
20/20 [==============================] - 0s 3ms/step - loss: 0.1054 - accuracy: 0.9688 - val_loss: 0.1475 - val_accuracy: 0.9500 - lr: 0.0010
Epoch 21/80
20/20 [==============================] - 0s 3ms/step - loss: 0.1309 - accuracy: 0.9531 - val_loss: 0.1389 - val_accuracy: 0.9563 - lr: 0.0010
Epoch 22/80
20/20 [==============================] - 0s 3ms/step - loss: 0.0995 - accuracy: 0.9719 - val_loss: 0.1037 - val_accuracy: 0.9750 - lr: 0.0010
Epoch 23/80
20/20 [==============================] - 0s 3ms/step - loss: 0.0845 - accuracy: 0.9641 - val_loss: 0.1159 - val_accuracy: 0.9750 - lr: 0.0010
Epoch 24/80
20/20 [==============================] - 0s 3ms/step - loss: 0.1072 - accuracy: 0.9609 - val_loss: 0.1514 - val_accuracy: 0.9563 - lr: 0.0010
Epoch 25/80
20/20 [==============================] - 0s 3ms/step - loss: 0.0860 - accuracy: 0.9688 - val_loss: 0.1160 - val_accuracy: 0.9688 - lr: 0.0010
Epoch 26/80
20/20 [==============================] - 0s 3ms/step - loss: 0.0836 - accuracy: 0.9672 - val_loss: 0.1490 - val_accuracy: 0.9563 - lr: 0.0010
Epoch 27/80
20/20 [==============================] - 0s 3ms/step - loss: 0.0704 - accuracy: 0.9766 - val_loss: 0.1089 - val_accuracy: 0.9750 - lr: 0.0010
Epoch 28/80
20/20 [==============================] - 0s 3ms/step - loss: 0.0922 - accuracy: 0.9656 - val_loss: 0.1366 - val_accuracy: 0.9688 - lr: 5.0000e-04

=== Test Session Metrics ===
Test Loss:     0.1593
Test Accuracy: 0.9602
scikit-learn not available, using NumPy-based metric evaluation.
Test Accuracy: 0.9602

Confusion Matrix:
[[10  0  0  0  0  0  0  0  0  0]
 [ 1 23  0  0  0  0  0  0  0  0]
 [ 0  0 18  0  0  0  0  0  0  0]
 [ 0  0  0 19  0  0  0  0  0  0]
 [ 0  0  0  0 20  0  0  0  0  0]
 [ 0  0  0  0  1 19  0  0  0  0]
 [ 0  0  0  0  1  0 20  1  0  0]
 [ 0  0  0  0  0  1  1 16  0  0]
 [ 0  0  0  0  0  0  0  0 24  1]
 [ 0  1  0  0  0  0  0  0  0 24]]
Macro Precision: 0.9580
Macro Recall:    0.9626
Macro F1-score:  0.9597

Saved MLP model: c:\Users\emrek\Desktop\HandGesture\GesturePorject\gesture_mlp.keras
Training history keys: ['loss', 'accuracy', 'val_loss', 'val_accuracy', 'lr']
Saved label map: c:\Users\emrek\Desktop\HandGesture\GesturePorject\gesture_mlp_label_map.npy
Saved feature scaler: c:\Users\emrek\Desktop\HandGesture\GesturePorject\gesture_mlp_scaler.npz

# GPT Frame

**1. Introduction**

- Briefly introduce the project goal:

- A machine learning-based hand gesture recognition system.
- Designed for **real-time input interpretation** using RGB camera data.

- State initial motivation:

- Alternative input system for VR and interactive environments.

- Clearly define **current project scope**:

- Shift from VR-specific solution → general-purpose gesture input interpreter.

- End with a short statement of what this report covers:

- Design evolution, tools, datasets, model decisions, and preliminary results.

---

**2. Project Objectives and Requirements**

- Define technical requirements:

- Real-time performance
- Low computational cost (background execution)
- High classification accuracy

- Functional requirements:

- Recognize predefined gesture set (10 classes)
- Support both hands

- Constraints:

- RGB-only input (no depth sensors)
- Consumer-level hardware compatibility

- Brief evaluation criteria:

- Accuracy
- Latency
- Scalability

---

**3. System Design Overview**

**3.1 Initial Design Approach**

- Describe original idea:

- Vision-based gesture recognition using full image input
- Consideration of temporal models (e.g., sequence-based approaches)

- Mention explored complexity (without going too deep yet)

**3.2 Design Shift and Rationale**

- Explain _why_ the approach changed:

- Computational cost
- Overengineering relative to project goals
- Real-time constraints

- Clearly justify:

- Why keypoint-based representation is sufficient
- Why static gesture classification is prioritized

**3.3 Final System Architecture (High-Level)**

- Pipeline overview:

1. Hand detection & keypoint extraction
2. Data preprocessing / normalization
3. Gesture classification (MLP)

- Emphasize modularity

---

**4. Tools and Technologies**

- Development environment:

- VS Code

- Libraries / frameworks:

- MediaPipe (hand tracking)
- ML framework (you’ll specify later: TensorFlow / PyTorch / etc.)

- Brief justification:

- Why MediaPipe is suitable (fast, reliable keypoints)

---

**5. Dataset Development**

**5.1 Data Collection Method**

- Self-collected dataset using MediaPipe inference
- Right-hand keypoint recording
- Controlled environment (you can expand later)

**5.2 Dataset Characteristics**

- Number of samples (~1000)
- Number of classes (10 gestures)
- Feature format (keypoint coordinates)

**5.3 Preprocessing Techniques**

- Normalization (scale/position invariance)
- Left-hand mirroring strategy:

- Transform left hand → right-hand equivalent

**5.4 Evaluation of Dataset**

- Strengths:

- Fast to generate
- Consistent labeling

- Limitations:

- Low diversity
- Potential overfitting risk

---

**6. Model Design**

**6.1 Model Selection**

- Choice of MLP (Multilayer Perceptron)
- Justification:

- Low computational cost
- Suitable for structured numerical input

**6.2 Input Representation**

- Keypoint vector structure
- Dimensionality (you’ll specify later)

**6.3 Training Process**

- Brief overview:

- Dataset split
- Training setup
- Loss function / optimizer (to be added later)

---

**7. System Implementation**

- Integration of MediaPipe with classification model
- Real-time inference pipeline
- Dual-hand processing:

- Parallel classification
- Left-hand mirroring adaptation

- Emphasis on efficiency and responsiveness

---

**8. Results and Evaluation**

_(You’ll expand this later with numbers)_

- Accuracy results (currently ~98%)
- Observations:

- Performance on trained gestures
- Stability across both hands

- Initial performance insights:

- Speed vs accuracy trade-off success

---

**9. Discussion**

- Critical evaluation of current system:

- Why the simplified model works well
- Trade-offs made (e.g., no temporal gestures)

- Limitations:

- Static-only gestures
- Dataset limitations

- Reflection on design decisions:

- Why abandoning complex models was beneficial

---

**10. Future Work**

- Potential improvements:

- Larger and more diverse dataset
- Adding dynamic gesture recognition (if needed)
- Optimization for deployment (CPU/GPU efficiency)

- Possible applications:

- VR
- Gaming
- Accessibility tools

---

**11. Conclusion**

- Summarize progress:

- Functional real-time gesture recognition system achieved

- Reinforce key achievement:

- High accuracy with low computational cost

- End with forward-looking statement:

- System is a strong foundation for further expansion

---

**12. References _(optional for now)_**

- MediaPipe documentation
- Any ML frameworks used