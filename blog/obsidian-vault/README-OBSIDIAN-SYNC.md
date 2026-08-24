# 🔮 Obsidian Vault - Adbongo Legacy Blog Archive

## What's Inside

This folder contains 23 blog posts from 2010-2012, formatted specifically for Obsidian with:

- ✅ Enhanced frontmatter with tags and metadata
- ✅ Topic backlinks ([[Sustainability]], [[Marketing]], etc.)
- ✅ Legacy content callouts
- ✅ Map of Content (MOC) index
- ✅ Topic notes for graph view connections

## 📁 Vault Structure

```
obsidian-vault/
├── 000-Blog-Archive-Index.md    # Start here - Main MOC
├── Topics/                       # Topic notes for backlinks
│   ├── Sustainability.md
│   ├── Permaculture.md
│   ├── Business.md
│   └── Marketing.md
└── [23 blog post files]
```

## 🚀 How to Import into Obsidian

### Option 1: Copy to Existing Vault (Recommended)

1. **Open your Obsidian vault folder** on your local machine
2. **Create a new folder** called `Adbongo-Archive` (or whatever you prefer)
3. **Copy all files** from this `obsidian-vault/` folder into it
4. **Open Obsidian** and you'll see the new notes appear
5. **Navigate to** `000-Blog-Archive-Index.md` to start browsing

### Option 2: Create New Vault

1. **Clone or pull this repo** to your local machine:
   ```bash
   cd ~/adbongo/adbongo.ai  # Or wherever your local repo is
   git pull origin main
   ```

2. **Open Obsidian**
3. Click **"Open folder as vault"**
4. Navigate to: `blog/obsidian-vault/`
5. Click "Open"

### Option 3: Sync with Git (Advanced)

If you want to keep the archive in sync with git:

1. Create a **symbolic link** from your Obsidian vault to this folder:
   ```bash
   # macOS/Linux
   cd ~/your-obsidian-vault/
   ln -s ~/adbongo/adbongo.ai/blog/obsidian-vault ./Adbongo-Archive
   
   # Windows (as Admin)
   mklink /D "C:\path\to\vault\Adbongo-Archive" "C:\path\to\adbongo.ai\blog\obsidian-vault"
   ```

2. Or use **Obsidian Git plugin** to manage the repo directly

## 🎯 Getting Started in Obsidian

Once imported:

1. **Open** `000-Blog-Archive-Index.md` - This is your hub
2. **Enable Graph View** (View → Graph View) to see connections
3. **Browse by year** or topic from the index
4. **Click on topic links** like [[Sustainability]] to see related posts
5. **Use backlinks panel** to explore connections

## 🏷️ Tags Reference

All posts include tags for easy filtering:

- `#legacy-blog` - All archived posts
- `#adbongo` - All Adbongo content
- `#archive-2010` - Posts from 2010
- `#archive-2011` - Posts from 2011
- `#archive-2012` - Posts from 2012
- `#sustainability` - Sustainability topics
- `#permaculture` - Permaculture/organic business
- `#business` - General business content
- `#marketing` - Marketing & branding

### Using Tags in Obsidian

- **Tag pane**: Click any tag to see all matching notes
- **Search**: Use `tag:#legacy-blog` to filter
- **Graph view**: Color by tags to visualize themes

## 🔗 Features for Obsidian

### 1. Backlinks
Click any topic link (e.g., [[Sustainability]]) to see all posts mentioning that topic.

### 2. Graph View
Visualize connections between posts and topics. Posts from the same year or theme cluster together.

### 3. Legacy Content Callouts
Each post has an info callout showing:
- Original publication date
- Related topics
- Archive context

### 4. Map of Content (MOC)
The index file (`000-Blog-Archive-Index.md`) serves as a central hub with links organized by year and topic.

### 5. Rich Metadata
Frontmatter includes:
- Title, date, author
- Post type and source
- Tags for filtering
- Aliases for alternate names

## 💡 Obsidian Tips

### Create Your Own Connections

Feel free to:
- Add [[wikilinks]] to other notes in your vault
- Create new topic pages
- Tag posts with your own system
- Add comments and annotations
- Link to current projects

### Recommended Plugins

- **Dataview** - Query and list posts by date/tag
- **Calendar** - Visualize posts by publication date
- **Graph Analysis** - Explore post connections
- **Tag Wrangler** - Manage and rename tags
- **Obsidian Git** - Sync with this repo

### Example Dataview Query

```dataview
TABLE date, author
FROM #legacy-blog 
WHERE contains(tags, "#sustainability")
SORT date DESC
```

## 📊 Stats

- **Total Notes**: 28 (23 posts + 1 index + 4 topics)
- **Time Span**: 2010-02-04 to 2012-10-08
- **Primary Topics**: Sustainability, Permaculture, Business, Marketing
- **Format**: Markdown with Obsidian enhancements

## 🔄 Keeping Updated

If new posts are added to the git archive:

1. **Pull updates** from the repo:
   ```bash
   git pull origin main
   ```

2. **Copy new files** to your Obsidian vault
3. Or **re-run the sync** if using symbolic links

## 📧 Questions?

Contact: baba@adbongo.io

## 🔗 External Links

- [GitHub Repo](https://github.com/Adbongo-Group-LLC/website)
- [Live Website](https://adbongo.ai)
- [Blog Archive (raw)](https://github.com/Adbongo-Group-LLC/website/tree/main/blog)

---

*Last updated: 2026-08-24*
*Prepared by: Cursor Cloud Agent*
