# Conjob Tutorial
## Editing cronjob in Linux
```bash
crontab -e
```

## Sample Syntax

It should have 5 '*' followed by command
```bash
* * * * * $command
```

## Reference
![reference](https://private-user-images.githubusercontent.com/23441168/315904998-9aee02c7-df38-4613-8b68-60ae33adfdfa.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MTEwODg1MzMsIm5iZiI6MTcxMTA4ODIzMywicGF0aCI6Ii8yMzQ0MTE2OC8zMTU5MDQ5OTgtOWFlZTAyYzctZGYzOC00NjEzLThiNjgtNjBhZTMzYWRmZGZhLnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNDAzMjIlMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjQwMzIyVDA2MTcxM1omWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPTBkNjY1M2E2ODFkZDc5Y2EyOTE5NTlhNDMzYTMwYTIwNjNlMjk2ZDkwMTNlNTkzYWViZmViMjcxNDJjZjM5ODkmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0JmFjdG9yX2lkPTAma2V5X2lkPTAmcmVwb19pZD0wIn0.pO8HQaIf3ug0oCleadypR6FGyP8DPD4uUJgLPhl6bHg)

## Other syntax

Cronjob will run every restart
```bash
@reboot echo "hello world"
```


