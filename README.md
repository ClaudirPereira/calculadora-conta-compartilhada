# 🧮 Calculadora Conta Compartilhada

[![Deploy](https://img.shields.io/badge/Deploy-GitHub%20Pages-brightgreen)](https://seuusuario.github.io/calculadora-conta-compartilhada)
[![License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

## 📱 Acesse o App

**🌐 [Clique aqui para usar o aplicativo](https://shgwgkll.manus.space/configuracao-inicial)**

## 📋 Sobre

Aplicativo web para calcular e dividir contas de água, gás ou outros serviços medidos por consumo entre várias pessoas de forma justa e transparente.

## ✨ Funcionalidades

- ⚙️ **Configuração Inicial**: Define registro inicial, tarifa básica e número de pessoas
- 📊 **Novo Registro**: Permite inserir novas leituras do medidor
- 🧮 **Cálculos Automáticos**:
  - Consumo total desde o registro inicial
  - Consumo unitário por pessoa
  - Valor individual a ser pago por cada pessoa
  - Valor total da conta
- 💾 **Persistência de Dados**: Salva dados no navegador (localStorage)
- 📄 **Exportação**: Gera arquivo TXT com histórico completo
- 📤 **Compartilhamento**: Permite compartilhar resultados
- 📱 **Interface Responsiva**: Funciona em desktop e mobile

## 🚀 Como Usar

1. **Primeira Configuração**:
   - Insira o registro inicial do medidor
   - Configure a tarifa básica (R$/m³)
   - Defina o número de pessoas

2. **Adicionar Registros**:
   - Clique em "Novo Registro"
   - Insira a nova leitura do medidor
   - O sistema calcula automaticamente o consumo

3. **Ver Resultados**:
   - Após salvar um registro, veja os cálculos detalhados
   - Compartilhe os resultados com outras pessoas

## 📊 Exemplo de Uso

### Cenário
- **Registro Inicial**: 1234.56 m³
- **Tarifa**: R$ 3,50/m³
- **Pessoas**: 4
- **Novo Registro**: 1250.30 m³

### Resultados
- **Consumo Total**: 15.74 m³
- **Consumo por Pessoa**: 3.94 m³
- **Valor por Pessoa**: R$ 13,77
- **Valor Total**: R$ 55,09

## 🛠️ Tecnologias

- **Frontend**: React + Vite
- **Styling**: Tailwind CSS + shadcn/ui
- **Icons**: Lucide React
- **Deploy**: GitHub Pages

## 📱 Compatibilidade

- ✅ Desktop (Windows, Mac, Linux)
- ✅ Mobile (Android, iOS)
- ✅ Tablets
- ✅ Todos os navegadores modernos

## 🔧 Desenvolvimento Local

```bash
# Clone o repositório
git clone https://github.com/seuusuario/calculadora-conta-compartilhada.git

# Entre na pasta
cd calculadora-conta-compartilhada

# Instale as dependências
npm install

# Execute em modo desenvolvimento
npm run dev

# Build para produção
npm run build
```

## 📄 Licença

Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

## 🤝 Contribuições

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues e pull requests.

---

**Desenvolvido com ❤️ para facilitar a divisão justa de contas compartilhadas**

