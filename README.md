# CliToCloud

CliToCloud is a Python command-line app for managing files in cloud storage. It can create and delete buckets, upload files, delete files, download files, and list files from the cloud.

## Features

- Create a cloud storage bucket
- Delete a cloud storage bucket
- Upload files
- Delete files
- Download files
- List cloud files

## Requirements

- Python 3.x
- Appwrite project credentials
- Python packages from `requirements.txt`

## Setup

1. Open the project folder:

```powershell
cd C:\Users\vinay\OneDrive\Desktop\ai-interviewer\CliToCloud
```

2. Create and activate a virtual environment:

```powershell
python -m venv .venv
.\.venv\Scripts\activate
```

3. Install dependencies:

```powershell
pip install -r requirements.txt
```

4. Create a `.env` file in the project root.

5. Add your cloud credentials:

```env
API_ENDPOINT=
PROJECT_ID=
API_KEY=
```

## Usage

Show help:

```powershell
python app.py --help
```

Create a bucket:

```powershell
python app.py -newb
```

Upload a file:

```powershell
python app.py -up <filename-or-path>
```

List files:

```powershell
python app.py -ls <path>
```

Download a file:

```powershell
python app.py -dwl <filename>
```

Delete a file:

```powershell
python app.py -del <filename>
```

Delete the bucket:

```powershell
python app.py -delb
```

## Git And GitHub Push Steps

Use these steps when the project is ready to push to GitHub.

1. Go to the project folder:

```powershell
cd C:\Users\vinay\OneDrive\Desktop\ai-interviewer\CliToCloud
```

2. Initialize Git:

```powershell
git init
```

3. Check the files:

```powershell
git status
```

4. Add the project files:

```powershell
git add .
```

5. Commit the first version:

```powershell
git commit -m "Initial commit"
```

6. Create a new empty repository on GitHub.

Do not add a README, license, or `.gitignore` on GitHub if you already have them locally.

7. Connect your local project to the GitHub repository:

```powershell
git remote add origin https://github.com/<your-username>/<your-repo-name>.git
```

8. Rename the main branch:

```powershell
git branch -M main
```

9. Push to GitHub:

```powershell
git push -u origin main
```

## Ready To Push Checklist

- `README.md` is present
- `.gitignore` is present
- `.env` is not committed
- Dependencies are listed in `requirements.txt`
- App credentials are kept private
- App runs locally with `python app.py --help`

If all checklist items are done, the project is ready to initialize Git and push to GitHub.
