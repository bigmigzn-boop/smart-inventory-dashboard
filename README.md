# smart-inventory-dashboard
Digitized supply inventory at the Pilot Plant using Excel: min-level modeling, alerts via formulas (IF/cross-sheet refs), conditional formatting, area-based views, and mobile data entry (linked sheet). Cuts inventory lead time, removes paper, reduces transcription errors, and standardizes the workflow.


# 🧪 Inventory Process Digitalization – Pilot Plant (PT/EN)

---

# 🇧🇷 Otimização do Controle de Insumos – Planta Piloto Kenvue

## 📘 Visão Geral
Este projeto apresenta a digitalização completa do processo de controle de insumos da Planta Piloto da Kenvue.  
A solução substitui o fluxo tradicional — baseado em papel e anotações manuais — por um sistema automatizado em Excel, com alertas inteligentes, formatação condicional e integração com dispositivos móveis.

---

## 📊 Planilha Automatizada de Estoque

### Tela Principal

![Planilha Principal](https://github.com/user-attachments/assets/56f15d86-bf6e-4e32-9441-829e674fc1b4)

A planilha utiliza fórmulas como:

```excel
=IF(D3<B3,"Abaixo do estoque",IF(D3<=B3+1,"Ficar Atento","OK"))
