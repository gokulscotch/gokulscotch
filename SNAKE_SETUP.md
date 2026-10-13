# 🐍 Snake Animation Setup Instructions

To make the contribution snake animation work on your GitHub profile (`gokulscotch/gokulscotch`), follow these simple steps:

---

### Step 1: Workflow File Already Prepared
The workflow file has already been created for you at:
`[snake.yml](.github/workflows/snake.yml)`

---

### Step 2: Enable GitHub Actions Permissions
1. Go to your repository on GitHub: `https://github.com/gokulscotch/gokulscotch` (or your repository name)
2. Click on **Settings** (tab at the top)
3. In the left sidebar, click on **Actions** → **General**
4. Scroll down to **Workflow permissions**
5. Select **Read and write permissions**
6. Click **Save**

---

### Step 3: Run the Workflow
1. Go to the **Actions** tab in your repository
2. In the left sidebar, click on **Generate Snake**
3. Click the **Run workflow** dropdown button on the right
4. Select the `main` branch and click **Run workflow**
5. Wait ~30 seconds for the action to complete with a green checkmark ✅

---

### Step 4: Verify Output
Once completed, the action automatically commits:
- `snake.svg`
- `snake-dark.svg`

into an `output` branch in your repository. The README is configured with responsive `<picture>` tags to automatically display the dark or light version according to the visitor's GitHub theme!
