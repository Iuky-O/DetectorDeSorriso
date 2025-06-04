# 🌟 Detector de Sorriso

Bem-vindo ao **Detector de Sorriso**! Aqui você vai poder identificar se a pessoa esta sorrindo ou não!

Quando alguém é identificado como sorrindo, um led acende no circuito com esp32 e led.

## 🧪 Tecnologias Utilizadas

- Python
- Esp32

## 🚀 Começando

Clone o repositório:

```bash
https://github.com/Iuky-O/DetectorDeSorriso.git
```

Abra no seu editor de código

## Criando o ambiente virtual

### 1. Criando

```bash
python -m venv venv
```
ou

```bash
python3 -m venv venv
```

### 2. Ativando
 
**🔹 Windows (CMD ou PowerShell):**
```bash
venv\Scripts\activate
```

**🔸 Linux / MacOS:**
```bash
source venv/bin/activate
```

### 3. Instalando as dependências

```bash
pip install -r requirements.txt
```

## 📚 Rodando

Para rodar você só precisa rodar este comando no terminal:

```bash
python Process.py
```

## 🐍 Caso não tenha a placa esp32
Caso você não tenha, pode utilizar apenas o detector de sorriso, para isso, comente estas linhas:

```python
#requests.get(f"{esp32_ip}/LED=ON")
...
#requests.get(f"{esp32_ip}/LED=OFF") 
```

Feito com ❤️ por [Iuky-O](https://github.com/Iuky-O)

