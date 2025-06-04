# 🌟 Detector de Sorriso

Bem-vindo ao **Detector de Sorriso**! Aqui você vai poder identificar se a pessoa esta sorrindo ou não!

Quando alguém é identificado como sorrindo, um led acende no circuito com esp32 e led.

## 🧪 Tecnologias Utilizadas

- Python
- Flask
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

### 1. **Rodando apenas o detector**

```bash
python Process.py
```

### 2. **Rodando detector + parte visual**

```bash
python app.py
```

Acesse com: http://127.0.0.1:5000

![image](https://github.com/user-attachments/assets/a15c62d0-a6b3-4993-93d3-0660ec10496e)
![image](https://github.com/user-attachments/assets/4f09080a-2fc4-4977-8da0-47c840ebadd5)



## 🐍 Caso não tenha a placa esp32
Caso você não tenha, pode utilizar apenas o detector de sorriso, para isso, comente estas linhas:

```python
#requests.get(f"{esp32_ip}/LED=ON")
...
#requests.get(f"{esp32_ip}/LED=OFF") 
```

Feito com ❤️ por [Iuky-O](https://github.com/Iuky-O)

