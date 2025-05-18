# 🚀 Laboratório Azure: Serviços de Computação em Nuvem

![Microsoft Azure](https://img.shields.io/badge/Microsoft_Azure-0089D6?style=for-the-badge&logo=microsoft-azure&logoColor=white)

## 📋 Sumário
- [Objetivos](#-objetivos)
- [Serviços Explorados](#%EF%B8%8F-serviços-explorados)
- [Configurações-Chave](#-configurações-chave)
- [Lições Aprendidas](#-lições-aprendidas)
- [Próximos Passos](#-próximos-passos)
- [Referências](#-referências)

## 🎯 Objetivos
Este laboratório prático demonstra a implementação de quatro pilares da computação em nuvem no Microsoft Azure:
1. Máquinas Virtuais (IaaS)
2. Conjuntos de Dimensionamento (Scale Sets)
3. Área de Trabalho Virtual (VDI)
4. Azure Functions (Serverless)

## ⚙️ Serviços Explorados

### 🖥️ Máquinas Virtuais
| **Configuração**       | **Detalhe**                              |
|------------------------|------------------------------------------|
| **Tipo**               | Windows Server 2022 Datacenter           |
| **Tamanho**            | Standard_B1s (1 vCPU, 1GB RAM)           |
| **Segurança**          | NSG com filtro por IP                    |
| **Otimização**         | Desligamento automático habilitado       |

**Comando CLI**:
```powershell
az vm create --name Machine-01 --resource-group MyRG --image Win2022Datacenter --size Standard_B1s
