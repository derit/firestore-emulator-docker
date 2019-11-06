### How to build
 
```bash
docker build . -t derit/firestore-emulator
```

### How to run

```bash
docker run --name firestore-emulator -d -e FIRESTORE_PROJECT_ID=test -p 8080:8080  derit/firestore-emulator
```