# Versões

`versions.json` guarda a versão atual de cada script da Almeida Scripts.

Os scripts leem este arquivo ao iniciar e, se houver versão mais nova que a instalada, avisam no console do servidor. É só uma leitura: nenhum dado do servidor é enviado. Para desligar, use `Config.VersionCheck = false` no `config.lua` do script.

---

`versions.json` holds the current version of each Almeida Scripts resource.

Resources read this file on start and print a notice in the server console when a newer version exists. It is a read only: no server data is sent. To turn it off, set `Config.VersionCheck = false` in the resource's `config.lua`.
