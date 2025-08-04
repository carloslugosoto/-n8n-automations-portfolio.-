# 🧾 Flujo n8n: Validador de Facturas de Proveedores vs Shopify

![Diagram_Flow_Check_Supplier_Invoices_Prices.png)  

*Valida discrepancias de precios entre facturas de proveedores, órdenes Shopify y cotizaciones*

## 🌟 Características Principales
- **Detección automática** de sobreprecios/subprecios
- **Integración con Google Sheets** para inputs/outputs
- **Reporte detallado** con diferencias calculadas
- **Lógica flexible** para adaptarse a distintos formatos

## 📋 Requisitos
1. Cuenta en [n8n](https://n8n.io/) (self-hosted o cloud)
2. Acceso a Google Sheets API
3. Hojas de cálculo con estos formatos:
   - **Órdenes Shopify**: `Order Number | Item SKU | Quantity`
   - **Cotizaciones**: `Item SKU | Unit Price`
   - **Facturas Proveedor**: `Order Number | Item SKU | Charged Unit Price | Quantity`

## 🚀 Cómo Empezar

### 1. Clonar repositorio
```bash
git clone https://github.com/tu-usuario/n8n-invoice-validator.git
cd n8n-invoice-validator
