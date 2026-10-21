# CLAUDE.md

This is Emre's personal Obsidian vault: worldbuilding, TTRPG campaigns, game design and video planning. It is a creative workspace, not a codebase. The user's own writing is the point; your job is to help organize, expand, cross-reference and check it without flattening its voice.

## The user's three rules: no exceptions

These override everything else in this file and any request that seems to conflict with them. If a task can't be done without breaking one, stop and ask.

### 1. The vault stays offline
Nothing from this vault (text, file names, images, summaries or paraphrases of them) leaves this machine unless the user specifically asks for that exact thing in that moment.
- Don't publish Artifacts, create Claude Docs, or use any connector (Google Drive, etc.) with vault content.
- Don't put vault content into a web search, a web fetch, a browser or a URL.
- Don't `git push`, and don't add or change git remotes. Commits stay local.
- Don't start cloud or remote sessions, or move this session to the cloud.
- Don't copy vault content outside the vault folder, except into Claude's own local scratchpad.
- The one unavoidable exception is that Claude itself runs on Anthropic's servers, so whatever Claude reads is processed there. Read only what the task needs.

### 2. Never edit or erase human-written text without a double confirmation
- Human-written means anything not inside an AI marker (see rule 3). Treat all existing content as human-written.
- To change or remove any of it, the user must ask for it **and then confirm again** after you have shown exactly what will change (the old text and the new text). Both steps are required, even for typo fixes, retagging, link fixes or reformatting.
- After any such edit, **always report it**: file, what was there before, and what it is now.
- Adding new AI text next to human text is allowed, as long as it's marked (rule 3) and the human text stays byte-for-byte unchanged.
- Never move or rename files or folders. Renaming rewrites links in other human-written notes.

### 3. Every AI-written section is marked
- **Inside a human note:** put AI text in a `claude` callout. It's self-contained and renders as a separate box in Obsidian:
  ```markdown
  > [!claude] Claude · 2026-10-21
  > AI tarafından yazılmış metin buraya.
  > - Liste de olabilir.
  ```
  Every line of the AI text starts with `> `. Put a blank line before and after the callout. Never put human text inside it.
- **A whole new note written by AI:** add `yazar: claude` to the frontmatter, and also put the body inside `> [!claude]` callouts. Then the note is still marked if it gets copied or merged.
- **Editing AI text that already exists:** allowed without confirmation, since it's AI-written. But if the user has typed inside a `claude` callout, treat that callout as human-written from then on.
- If the user moves AI text out of its callout, it counts as theirs from then on.
- Exceptions: config files that belong to Claude (`CLAUDE.md`, `.claude/`) and `Şablonlar/` don't need markers.

## Language

- **Notes are written in Turkish.** Anything you write *into* the vault (new notes, additions, summaries, templates) is in Turkish, matching the user's tone. English terms the user already mixes in (game design jargon, "session", "arc", "boss", "tier", "cooldown"...) are fine to keep.
- Talk to the user in whatever language they write to you in.
- Keep the user's spelling of names exactly, including apostrophes and capitals: Aldha'Menor, Far'Yadox, Jish'Ajinn, Arhun'Tila, Nea'Vaii. Never "correct" invented words.

## Vault map

| Folder | What it is | Status |
|---|---|---|
| `Fabulous/` | **Fabulous Diyarı**: the main fantasy world. Magic systems (`Büyü Sistemleri/`), the regions and peoples of Erikan (`Erikan/`), myths, ages, a glossary (`Sözlük.md`), themes (`Temalar.md`). Overview canvas: `Fabulous/Fabolous Diyarı.canvas`. | Active, long-term |
| `FRP - TTRPG/Naxal ve Düşünce İğnesi/` | TTRPG campaign. `Karakterler/` (PCs and key NPCs), `Hikaye & Olay Dizisi/` (factions, locations, plot threads), `Arşiv/` (session log with XP tracking, combat, items, tone), `Karalama/` (scratch), `SONRAKİ SESSİONLAR İÇİN.md` (prep). | Active campaign |
| `FRP - TTRPG/Emenos'un Gölgeli Sokakları/` | TTRPG campaign (city intrigue). `Karakterler/`, `Taraflar.md` (factions), `OLAYLAR.md`, `Geçmiş Session'lar deposu.md`, `Sonraki Session Notları.md`. | Active campaign |
| `FRP - TTRPG/SYSTEM DESIGN/` | The user's own homebrew TTRPG system: `NERRATIVE SYSTEM.md`, design philosophy in `Style Notes.md`, campaign drafts. | In development |
| `FRP - TTRPG/Cyberpunk/` | Character sheet for another game. | Minor |
| `OYUNLAR/` | Video game projects, each in its own folder: Asena Oyun, WinterTale, ForABetterDay, KSM, FasterPunch, Fabulous Centuries (card game). | Mixed; Fabulous Centuries is suspended indefinitely |
| `VİDEOLAR/` | Video ideas (`Fikir Kutusu.md`), in-progress and past video projects. | Active |
| `NOTLAR/` | General learning notes (e.g. Blender). | Misc |
| `DONE & GONE/` | Finished or archived work (graduation project). **Read-only reference; don't edit.** | Archived |
| `Wahirion - Zihin Zinciri.md` | Year plan / personal roadmap by month. Check it for what's currently prioritized. | Active |
| `Şablonlar/` | Note templates (see below). | — |
| `attachments/` | All images. Obsidian saves pasted images here. | — |

If the user asks "what am I working on" or what should come next, look at `Wahirion - Zihin Zinciri.md` first.

**Project briefs:** `Fabulous/`, `FRP - TTRPG/Naxal ve Düşünce İğnesi/` and `FRP - TTRPG/Emenos'un Gölgeli Sokakları/` each have their own `CLAUDE.md`, with the premise, factions, current state and known inconsistencies. They load automatically when you work in that folder. Read the relevant one before touching a project from elsewhere. When the user adds sessions or lore, offer to update the brief's "Where things stand" section.

## Obsidian conventions

- **Links:** `[[Note Name]]`, using the file name without `.md`. A link to a heading is `[[Note#Başlık]]`, and an alias is `[[Note|görünen metin]]`. Before linking, check that the target note exists. If it doesn't, either leave a deliberate unresolved link (that's how the user marks "to be written" notes) or ask.
- **Images:** `![[file.jpg|180]]`. The number is the display width (the user typically uses ~170–185). Image files live in `attachments/`. Many character image file names hold a one-line description of the character, so they're worth reading as notes.
- **Tags:** inline `#tag` at the end of a note. **Use lowercase for new tags.** Existing tags are inconsistent (`#dnd` vs `#DnD`, `#rpg` vs `#RPG`); don't mass-retag without asking. `#tasarlanacak` means "to be designed".
- **Properties (frontmatter):** most existing notes have none. New notes made from templates use the properties below. Don't add frontmatter to existing notes unless asked.
- **Canvas files (`.canvas`)** are JSON (nodes + edges). Only edit them if asked, keep the JSON valid, and keep existing node ids and positions.
- **Bases (`.base`)** are YAML view definitions for the Bases core plugin.

### Properties used by templates

| Key | Values |
|---|---|
| `tür` | `karakter`, `session`, `mekan`, `taraf`, `oyun-tasarımı` |
| `proje` | campaign, world or game name as a link, e.g. `"[[Naxal ve Düşünce İğnesi]]"`, or plain text |
| `durum` | `taslak` (draft), `aktif`, `kanon` (settled canon), `askıda` (on hold), `bitti` (done) |
| `tags` | Obsidian's standard tag list, lowercase |

## Other working rules

1. **Never rename or move notes or attachments.** Obsidian only rewrites `[[links]]` for renames done inside the app, so a rename from outside breaks every backlink. If a rename seems useful, suggest it and let the user do it in Obsidian.
2. **Never delete notes, images or content.** If something looks like a duplicate or junk, point it out and let the user decide.
3. **Don't touch `.obsidian/`** (settings, theme, workspace).
4. **Write in the user's voice.** When adding marked AI text, match their style: informal, dense, idea-first, with half-sentences and parentheses.
5. **Canon vs. draft.** Treat `Karalama/` notes, "Karalama Alanı" files, `Fikir Kutusu.md` and struck-through (`~~ ~~`) text as brainstorming, not canon. When checking lore consistency, say which source a fact came from and flag contradictions instead of silently resolving them.
6. **Commit before big changes.** Before a multi-file edit, suggest a local commit so the user can roll back. Commit only when asked, and never push (rule 1).

## Useful workflows

- **Session prep:** read the campaign's "next session" note, the last entries of the session log and the relevant character/faction notes, then propose scenes, NPC beats and open threads. Write these into the prep note only if asked.
- **Session log:** follow the existing format in `Arşiv/Session Takip ve Notları.md` (`# N :`, date `GG/AA/YYYY`, `XP:` line, then prose).
- **New character / location / faction:** start from the matching template in `Şablonlar/`, link it from the relevant hub note, and reuse images already in `attachments/` when they match.
- **Lore questions:** search the whole vault (names often appear in image file names and canvases too), and quote the note you're relying on.
