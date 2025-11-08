## Usage
```seq 1 1000 | ./hashit.sh b64 | ffuf -w - -u 'http://example.com/user?id=FUZZ'```
