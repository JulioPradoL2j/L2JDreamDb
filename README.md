## 3️⃣ Rodar o banco de dados

Após a instalação do MariaDB:

- Vá até a pasta `tools/` do projeto
- Execute o script correspondente ao seu sistema operacional para importar as tabelas e dados iniciais:

### ✅ No **Windows**:
```bat
install_db.bat
```

### ✅ No **Linux**:
```bash
chmod +x install_db.sh
./install_db.sh
```

> Você também pode usar um cliente como HeidiSQL, DBeaver ou MySQL Workbench para importar manualmente os arquivos `.sql` da pasta `tools/sql`.
