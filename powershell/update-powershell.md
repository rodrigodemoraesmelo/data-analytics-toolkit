# ⬆️ Atualizar o PowerShell pelo WinGet

Comando rápido para atualizar a versão estável mais recente do **PowerShell** diretamente pelo terminal utilizando o **Windows Package Manager (WinGet)**.

## 🚀 Atualizar

Execute no PowerShell:

```powershell
winget upgrade --id Microsoft.PowerShell --exact --source winget
```

## ✅ Verificar a versão instalada

Após a atualização, abra uma nova sessão do PowerShell e execute:

```powershell
$PSVersionTable.PSVersion
```

## 💡 Quando usar?

Útil quando o PowerShell informar que existe uma nova versão estável disponível e você quiser realizar a atualização diretamente pelo terminal, sem baixar manualmente o instalador.

---

> Este conteúdo faz parte do **Data Analytics Toolkit**, uma coleção de soluções, comandos e aprendizados que surgiram de necessidades reais do dia a dia.
