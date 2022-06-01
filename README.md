# A repository where you can find ADTs dumped from various iDevices

Please censor your serials, MACs and IMEIs.

Please keep the socname/devicename.adt structure.

## Example dump guide
```
git clone https://github.com/checkra1n/PongoOS

cd PongoOS

<get your device into pongo os with checkra1n>

python3 scripts/issue_cmd.py dt
python3 scripts/fetch_stdout.py > n61.adt

<open the file and CENSOR YOUR IMEI, MAC, SERIAL, (potentially) NVRAM and unique identifiers!>
```
