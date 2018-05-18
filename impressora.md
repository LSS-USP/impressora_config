1. Tenha o `cups` instalado na máquina

2. Tenha certeza que o CUPS está rodando (normalmente ele escuta na porta 631)
```
$ sudo systemctl status cups.service
$ sudo netstat -nltp | grep cups
```

3. Acesse `localhost:631`

4. Vá em `Adicionar Impressoras` (talvez esteja em inglês)

5. Preencha com seus dados

6. Utilize `ipp` (`ips` dá merda)

7. Preencha os campos óbvios (a impressora do lab é uma HP)

8. Quando for necessário preencher o modelo, selecione
`HP LaserJet P3010 Series Postscript (recommended) (en, da, de, es, fi, fr, it, ja, ko, nl, nb, pt, sv, zh_CN, zh_TW, ru) ` 

