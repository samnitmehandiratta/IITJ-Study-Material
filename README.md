# IITJ Study Material

A centralized repository for organizing study materials across different subjects at IIT Jodhpur.

## 📁 Folder Structure

- **Foundational Models and Generative AI**
- **Hardware Design for AI**
- **VCC**
- **Systems Engineering**

## 📤 How to Contribute via Pull Request

If you'd like to add study materials to this repository, follow these steps:

### Step 1: Fork the Repository

1. Go to the [repository page](https://github.com/samnitmehandiratta/IITJ-Study-Material)
2. Click the **Fork** button (top-right corner)
3. This creates a copy of the repository under your GitHub account

### Step 2: Clone Your Fork

```bash
git clone https://github.com/<your-username>/IITJ-Study-Material.git
cd IITJ-Study-Material
```

### Step 3: Create a Personal Folder (Important!)

To avoid merge conflicts with other contributors, **create a folder with your name** inside the subject folder before adding your files.

```bash
# Example: Create your own folder inside VCC
mkdir -p "VCC/<your-name>"

# e.g., mkdir -p "VCC/Samnit-Mehandiratta"
```

This ensures everyone works in their own space and PRs don't conflict with each other.

### Step 4: Add Your Files

1. Navigate to your personal folder inside the appropriate subject folder
2. Add your files (PDFs, notes, presentations, etc.)

```bash
# Example: Add a PDF to your personal folder
cp /path/to/your/file.pdf "VCC/<your-name>/"

# Or create subfolders for specific topics
mkdir -p "VCC/<your-name>/Lecture Notes"
```

### Step 5: Commit and Push to Your Fork

```bash
git add .
git commit -m "Add [file/topic] to [subject name]"
git push origin main
```

### Step 6: Create a Pull Request

1. Go to the **original repository** ([samnitmehandiratta/IITJ-Study-Material](https://github.com/samnitmehandiratta/IITJ-Study-Material))
2. Click the **Pull Requests** tab
3. Click **New Pull Request**
4. Click **compare across forks**
5. Select **your fork** as the head repository and **main** branch
6. Review your changes
7. Add a meaningful title and description
8. Click **Create Pull Request**

### Alternative: Via GitHub Web Interface

1. Fork the repository on GitHub
2. Navigate to the desired subject folder in your fork
3. **Create a folder with your name** (click **Add file** → **New file**, then type `Your-Name/` to create a folder)
4. Click **Add file** → **Upload files** inside your folder
5. Drag and drop your files
6. Commit the changes
7. Click **Contribute** → **Open Pull Request**

## 📝 Guidelines

- **Always create a personal folder** inside the subject directory to avoid merge conflicts
- Name your files clearly (e.g., `Lecture-01-Introduction.pdf`)
- Keep file sizes reasonable (< 25 MB per file)
- Organize content into logical subfolders within your personal folder
- One pull request per subject/topic is preferred

## ❓ Need Help?

Open an issue or reach out to the repository maintainer.
