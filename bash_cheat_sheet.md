1. Check if a Program Exists
```bash
if command -v your_program_name &> /dev/null
then
    echo "Program exists"
else
    echo "Program does not exist"
fi
```

2. Read Input with a Prompt
```bash
read -p "Enter your name: " name
echo "Hello, $name!"
```

3. Loop Through Files in a Directory
```bash
for file in /your/directory/path/*
do
  echo "$file"
done
```

4. Check if a File Exists
```bash
if [ -f "/path/to/your/file.txt" ]; then
    echo "File exists."
else
    echo "File does not exist."
fi
```

5. Download a File with curl
```bash
curl -O http://example.com/yourfile.txt
```

6. Extract a tar.gz File
```bash
tar -xzvf yourfile.tar.gz
```

7. Find and Replace Text in a File with sed
```bash
sed -i 's/old-text/new-text/g' yourfile.txt
```

8. Check Disk Usage of a Directory
```bash
du -sh /path/to/directory
```

9. Display Lines Containing a Specific String with grep
```bash
grep "your-string" /path/to/file
```

10. Send an Email with mailx
```bash
echo "This is the email body" | mailx -s "Email Subject" user@example.com
```

11. Create a ZIP Archive of a Directory
```bash
zip -r archive_name.zip /path/to/your/directory
```

12. Schedule a Job with cron (edit crontab)
```bash
crontab -e
# Add a line for the schedule, for example, to run a script daily at 5 pm:
# 0 17 * * * /path/to/your/script.sh
```

13. Get the Current Date and Time
```bash
echo "Current date and time: $(date '+%Y-%m-%d %H:%M:%S')"
```

14. Check if a Directory Exists
```bash
if [ -d "/path/to/your/directory" ]; then
    echo "Directory exists."
else
    echo "Directory does not exist."
fi
```

15. Iterate Over a Range of Numbers
```bash
for i in {1..10}
do
   echo "Number $i"
done
```