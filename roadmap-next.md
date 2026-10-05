### New

**All projects**
- A page with every project you can reach: cover cards or a list, newest opened first, or by name, start date or phase. Open it from the switcher's "All projects", Ctrl+K, or the empty screen.
- Filter by phase, client and workspace (pick several), search, and show archived projects when you need them.
- Admins set the phase (now with Done), rename a project and archive it from a card's menu. Renaming changes the name only; the folder and the project ID stay.
- Edit Project now also edits the name and the start date (the schedule follows; the project ID keeps its date).
- Archived projects leave the switcher and the lists, stay findable by search, and show "Archived" on Home. Done and archived projects stay quiet on Discord.

**A quicker project switcher**
- The title-bar switcher stays small however many projects there are: up to six rows, pinned projects first, then the ones you opened last on this PC ("Opened 2d ago"; "Started …" for ones you haven't opened here). "All projects" shows the rest.
- Pin a project from its row (the pin on hover, or the ⋯ menu, which also opens the folder in Explorer and copies the project ID). Pins are per PC.
- Typing searches every project; arrow keys pick, Enter opens.
- Asset and shot counts fill in a moment after the list opens instead of holding it up.
- Open Project on a folder of projects lists them with "Use as workspace"; it no longer switches your workspace by itself.
- Picking a project whose folder is gone says so and drops it from the list.

**Ask does more**
- Ask: a Stop button ends an answer while it is being written, and Retry asks the last question again.
- Ask conversations are still there after you restart Monos, on this PC: each item's, and the palette's for each project. Switching project in the palette brings back that project's conversation instead of starting over.
- The palette's Ask knows what is on screen: on Assets or Shots it knows the selected item and department, so "is this published?" just works.
- Ask can now do things for you, each after you click Confirm on a card that says exactly what will happen: write a note on an asset or shot (with @mentions, who are told as with any note), set a department's status (or back to Automatic), and copy files from an Inbox drop to where they belong (the Inbox keeps them).
- Ask reads documents: the text of a script, brief or guideline in the Project Guide or the Inbox (PDF, Word, text), a few PDF pages at a time.
- Ask searches the studio Library by words, category or tag.
- Answers can show pictures: an item's thumbnail, a rendered frame, a reference or Library preview. Click one to open it.
- New watches: "tell me about new notes on sh010" (or anywhere in the project), and a morning report every day at the time you pick, in Monos and on Discord: renders that failed or finished, publishes, notes for you, Inbox drops.
- The Ask chat stays on the newest message when a card is answered or a picture loads, and the "more below" arrow no longer shows at the very bottom of a list.
- A confirm card can also be answered by typing: "ok", "có", "đồng ý" confirm it, "không", "thôi", "cancel" cancel it, when only one card is waiting. Asking for a change instead makes a new card that replaces the old one.
- Answers flow in smoothly: the text appears at an even pace instead of in bursts, the newest words fade in, and the lead-in and "Checking …" lines fade in too.
- New lines push the Ask chat up with a short glide instead of a jump.

**Project format in Settings › Pipeline › Format**
- Set what a project works in with a few clicks: frame rate, start frame and handles are chips (Other for anything else), resolution is a list of common sizes plus Custom, then the colour config and working space. Pixel aspect waits behind "More".
- List what it delivers: one card per output (resolution, frame rate, codec and container, colour and bit depth, audio, file name pattern with an example), one marked primary. An output is "Same as working" for resolution and frame rate until you untick it. "Add output" starts from Master, Client review, Social 9:16 or EXR sequence, and file names take tokens or a pattern with a click.
- Start from a studio preset (TVC 4K, HD and Social 9:16 at 25 or 30 fps, HD 24 and Film 2K 24 ship with Monos), or edit the studio's own presets under Studio defaults. Changing a preset never changes projects already made from it.
- Studio admins edit; everyone else sees it read-only. Nothing is written until Save.
- The project's format shows under its name on Home, and a Deliverables card lists its outputs (admins get Edit / Set up, which opens Settings › Format).
- New Project has a Format field: pick a studio preset and the project starts with it, or leave it for later.
- Inspector › Details checks the latest preview against the format: a quiet tick when the frame rate, resolution or first frame match, the warning colour and the expected value when they don't, plus one sentence on what to check. A half- or quarter-size preview is fine (it says so). PNG / JPG sequences show their playback rate as "(playback)" and aren't compared.
- A Format row in Details shows what the item works in ("50 fps · 3840×2160 · from 993"), tagged Shot when the shot has its own. Admins click it to override a shot's frame rate, resolution, start frame or handles, or clear the override.
- Create new opens Blender, Maya, Houdini and Fusion files already set to the format: frame rate, resolution and the first frame (start frame minus handles), with a shot's own override when it has one. Houdini takes the frame rate and range (it has no scene resolution); assets get the frame rate only. Files that already exist are never changed.
- Image sequences in the Inspector and the review player play at the project's frame rate (a shot's own rate when it has one) instead of the Settings default, unless the files say otherwise.

**Monos mind: what Monos knows**
- Ask can now explain how to use Monos: where a page is, how to make a work file, what the Inbox does, which key does what. It answers from topics that come with Monos and are kept up to date with each version, and links like "Open the Outbox" in an answer take you there.
- Admins can teach Monos how the studio works in Settings › Assistant › Monos mind: write a topic once (how you name files, deliver to clients, handle renders), for every project or just one, and Monos uses it when a question needs it.
- A built-in topic your studio does differently can be hidden there.
- The answer's "Checked" line says which topic Monos read.

**Monos shows you the way**
- Ask "how do I make a work file for Ronin?" in the ` palette and Monos shows you on screen instead of writing the steps out: it shrinks to a small circle with a speech bubble, and a purple cursor of its own points at each button in turn.
- That cursor never clicks anything. You click the button it points at, and it moves on to the next one. Click somewhere else and the bubble tells you; Next skips a step, Esc or the close button ends it.
- Guides so far: making a work file, sending an Inbox file to a Project Guide folder, writing a note, changing the theme, opening another project, adding a Monos mind topic, opening the review player on a shot's latest preview, copying a work file from one shot or asset to another, and switching Assets or Shots to Work, Published or Review.
- For other how-to questions Monos can put a guide together itself from Monos mind, and it can now point at any button or menu row by its label, and at the Work / Published / Review pill. The bubble says so on every step ("Monos worked this out from Monos mind. It isn't a checked guide."), and at the end asks "Did this work?".
- Admins see those questions, with what people answered and which steps they skipped, in Settings › Assistant › Monos mind under "How-to questions Monos had to work out": the ones that need a guide built into Monos.
- An admin can also turn on "Share these with the Monos team" there (off by default). Each answer to "Did this work?" then goes to the people who make Monos, with file names, project names and people's names taken out, so the next versions can build those guides in.
- In the Inspector's Ask tab the answer gets a "Show me" button instead, so a guide never starts while you're working on an item.

**Recent workspaces in Settings › Workspace**
- Lists the workspace in use and the folders of the projects you opened recently, with how many projects each holds. Click one to switch to it.

**Profile pages**
- Everyone has a page: their photo, name, role, departments, Discord name and when they joined this project, with everything they did on it (notes, replies, comments, new assets and shots, work files, imports). Older activity loads as you scroll.
- The page shows how much they did (notes, replies, assets and shots made, work files, imports), when they joined the studio, and their e-mail on your own page. Edit profile on your page; admins get Edit in Team on others'.
- Open it by clicking a name or face anywhere on Home (posts, comments, replies), a name in Settings > Team, a person in the footer's team list, or My profile in your account menu. Back and Forward work between pages and people.
- Who published or rendered isn't recorded yet, so those posts only show on a page when the person commented on them.

### Changed

**Home is quicker to act on**
- Right-click anything on Home for what you can do with it: a post (Reply, Resolve, Play, Open folder, Copy path, Show in Shots…), a picture (View, Copy picture, Show in Explorer), a comment or reply (Copy text, Open note), a Needs attention row (each item by name), the cover and empty space (Refresh, Edit project, Change cover).
- Every post has a ⋯ button with the same menu. Deleting your own note moved there with the rest.
- A Needs attention row selects all its items on their page ("Selected 5 blocked shots"), not just the first one. "+N more" opens the other rows in place.
- Click a department in Progress to open Shots or Assets with that department on.
- Copy text copies the whole note, line breaks included.
- Notes and replies on Home keep their line breaks, as in the Inspector.
- "View N more" opens the whole conversation right in the feed; "Show fewer" folds it again.
- Show in Shots on a post about several shots selects all of them, with the post's department on.
- Comments on a publish or render work like Facebook: the name on its own line, replies folded behind "View N replies" and nested under the comment once opened. Replying opens them so you see yours land.
- A client's or freelancer's name in a post carries a Client / Freelancer tag, so it never reads like a team member.
- Clients and freelancers have a page too: their photo and note from Manage senders, first and last drop, how many drops and files, how many are sorted and still to sort, and their drops. Open in Inbox from there shows only theirs.
- A People card on Home lists the team (as in Settings > Team, split into Online and Offline with a presence dot, like the footer) and the clients / freelancers of the project, one per row; a click opens their page, even for someone with no posts yet.
- Clients' and freelancers' photos from Manage senders show on Home (their drops and the People card) when projects share a folder.
- Click a shot or asset name in a post to open it (with the post's department on); it underlines under the pointer.
- Delete your own comment or reply right in the feed (Delete button or right-click; admins can delete any), with Undo.

**Home moves more smoothly**
- The reply box opens and folds instead of popping; the posts below move with it.
- Progress bars ease to their new values; the filter list's highlight slides to the filter you pick.
- While Home loads you see the outline of posts and cards instead of an empty page or "All clear." too early. If loading fails, Home says so.
- On the Light theme the Progress bars show "not started" clearly.
- Home has a scroll bar, and older activity loads by itself as you reach the bottom (no more Show older button). Right-click offers Back to top and Go to bottom.
- Going somewhere from Home and coming Back puts the feed where you left it.
- Keys on Home and profile pages: Page Up / Page Down scroll a screen, Home / End go to the top / bottom, F5 refreshes and goes back to the top (not while you're typing a reply): a diagonal shimmer runs over the feed and the side cards, and the fresh posts fade gently back in once it is halfway across, with no jump or flicker.
- Find older posts by date: each day in the feed has its own divider (Today, Yesterday, Mon 28 Sep), and while you scroll a date chip at the top says which day you are on. Click it to jump to Today, This week, Last week or any month; Home loads the posts down to it first.
- Home stays smooth with hundreds of posts: switching Overview / Notes is instant again (it rebuilt every loaded post, up to several seconds), older posts load ahead of the bottom without a hitch, and the Notes tab loads a page at a time too.

**Drag files out with the middle mouse button, everywhere**
- Hold the middle button on a card and drag it into Explorer, Fusion, After Effects, Resolve or a chat. It works the same on Assets and Shots, the Inspector picture, the Library, the Inbox / Outbox and the Project Guide, with no grip to find first.
- On Assets and Shots the card hands over what you are looking at: the work file in Work, the shot's review folder (an asset's picture) in Review, and every file of the newest publish in Published.
- Drag one card of a multi-selection and the whole selection goes along. The picture under the cursor is a small rounded card (thumbnail and name), stacked with a count when several go.
- The left button now always selects: a left drag that starts on a tile draws the selection box in the Inbox, Outbox and Project Guide too.

**Monos has a face of its own**
- The assistant has its own mark everywhere: a rounded play triangle with one eye, in place of the sparkles. It shows what Monos is doing: a ring circles it while Monos thinks, the eye moves while it writes, and it bounces once when an answer is done. The title-bar button shows it thinking while an answer is written.
- A confirm card answers in place: Confirmed or Cancelled appears where the buttons were, so the conversation no longer jumps.
- The ` palette can be dragged by its header while it is open (double-click the header to put it back). It always opens in the same place.

**Guides look clearer**
- Monos itself points the way: its cursor is the same rounded triangle, and it takes a gentle curve to each control.
- The control is lit by a soft spotlight that follows its shape, centred even at the edge of the window, with one thin ring.
- "Show me" in the palette: the palette closes into Monos, which pops up, blinks, says the first step, and only then sets off.
- While the cursor moves the bubble tucks into Monos, and springs back out with the next step when it lands. Monos looks toward its cursor and blinks at each new step.

**Assets and Shots keep up with the disk**
- Save a work file from your DCC, copy in a publish, or let a render finish: the card updates by itself within a second or two, with no project reload. Only that card changes; your selection, scroll position and the Inspector stay put.
- Publishes and renders now show up live too, also when they arrive from another PC through Dropbox. A render still writing frames updates once it settles, not on every frame.
- New Asset, New Shot, Rename, Set status and Move to Trash update just those items, so big projects no longer pause to reload. A renamed asset stays selected.

### Fixed

**Rename and Move to Trash work while Monos is open**
- Renaming or moving an asset to Trash, in Monos or in Explorer, no longer fails with "access denied" because Monos itself was holding the folder.
- When a file of the asset really is open somewhere, Rename says which one within a couple of seconds instead of freezing the window for about 20 seconds, and keeps the name you typed.

**Settings › Pipeline opens without a freeze**
- Clicking Pipeline in Settings no longer freezes the window for half a second, every time. The page shows at once and scrolls straight away.
- The apps list on a department (APPS) opens instantly on any row.
- On PCs running tools like UniKey or PowerToys, Monos no longer pauses on clicks that change many buttons at once. Screen readers no longer see Monos' buttons; set MONOS_ACCESSIBILITY=1 to bring that back.

**Create New closes after the work file is made**
- In 27.11.0 the Create New dialog stayed open after "Create and open" had made the file and opened the app, and a second click said the item wasn't available any more. It closes again.

**Creating a project is safer**
- New Project says right away when a project with the same ID is already in the folder, before you click Create.
- Creating a project can no longer remove a folder someone else just made with the same name.
- A new project starts with the asset types and departments of the studio it is created in, even when another workspace is open.
- The window stays responsive while a project is created on a slow drive.
- A project created or opened outside your workspace now shows in the project switcher; recently opened projects come first, and a project from another folder says which folder it is in.
- Project rows are quieter and easier to scan: the project's cover (or a coloured tile with its first letter), the name with its phase from Edit Project, then counts. The folder ID only shows when two projects share a name, the open project is marked "Open", and hovering a row shows its full path.
- After creating a project, asset, shot or sequence, the next one no longer opens stuck on "Creating…".

**No more Dropbox conflicted copies from the assistant**
- The studio's background services (watches and the Discord bot) no longer fill the studio's Dropbox folder with "conflicted copy" files when several PCs have Monos open. Update every PC: an older Monos still writes the old shared file.
