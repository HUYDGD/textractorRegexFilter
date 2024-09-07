# textractorRegexFilter
Regex filter for textractor

The regex pattern filters out a variety of special characters, as well as the letter "r".
[><\/!@#\$%\^\&\*\(\)\-\+=\[\]\{\};:'",\.\?\\|`~r]

This regex will filter out:
All special characters
The letter "r" (in both lowercase and uppercase)
Everything else (alphanumeric characters, spaces, Chinese, Japanese characters) will be kept intact.
[^a-zA-Z0-9\s\u4E00-\u9FFF\u3040-\u309F\u30A0-\u30FFrR]


