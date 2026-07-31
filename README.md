# AutomaticResumeEditor

A Python script that tailors your resume to a specific LinkedIn job posting using AI-generated keyword optimization.

## Usage

1. Run the script in your Python terminal.
2. Enter the path to your resume document when prompted.
3. Paste the link to your job posting on LinkedIn.
4. Enjoy your newly tailored resume!

## Requirements

- Python 3
- `requests`
- `beautifulsoup4`
- `python-docx`
- `groq`

Install dependencies with:

```bash
pip install requests beautifulsoup4 python-docx groq
```

## Setup

You'll need a [Groq API key](https://console.groq.com/keys). The script will prompt you to enter it when it runs.

If you'd rather not enter it every time, you can set it as an environment variable instead:

```bash
export GROQ_API_KEY=your_key_here
```

## Output

The tailored resume is saved as:

```
<original_resume_name>_<job_title>.docx
```
