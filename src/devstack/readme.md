## fire up the stack

```powershell
./up.ps1
```

## tear it down

This will destroy the stack, volumes will persist so data should be lost if correctly mapped in the `docker-compose.yml`
  
```powershell
./down.ps1
```

## Check the state of your stack

```powershell
docker stack ps devstack
```