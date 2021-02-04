1. Edit the shell profile with the following command:
```bash
nano .profile
```

2. Add the following line to the end of the file:
```bash
source infraclass/config
```

3. Save the file

4. Close and re-open Cloud Shell

5. Use echo command to verfy that variable is still set:
```bash
echo $INFRACLASS_PROJECT_ID
```
