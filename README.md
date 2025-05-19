
# 📚 Projeto: Gestão de Documentos

Este projeto foi desenvolvido como atividade da disciplina de Desenvolvimento Web I, abordando alguns dos principais tópicos avançados de Django.

## ✅ Funcionalidades Implementadas
- Custom User Model (Login via e-mail)
- Upload de Documentos com validações de tipo e tamanho
- Caminho de upload dinâmico e nomes de arquivos únicos
- Context Processors para variáveis globais
- Custom Managers e QuerySets personalizados
- Admin personalizado (filtros, inlines e ações customizadas)
- Django Messages para feedback de ações
- Logging de ações e exceções
- Decorators para controle de acesso e log de execução

## 🚀 Instruções de Instalação

```bash
git clone <este-repositorio>
cd gestao_documentos
python -m venv venv
source venv/bin/activate  # ou venv\Scripts\activate no Windows
pip install -r requirements.txt
python manage.py migrate
python manage.py createsuperuser
python manage.py runserver
```

## 📌 Atividade
Implemente novos filtros no admin para listar documentos por data de envio e tamanho.  
Adicione uma action customizada para marcar documentos como "Verificados".  
Crie um decorator que registre no log o usuário que realizou uploads de arquivos.  

---

## 🤝 **Dúvidas?**

Caso tenha dúvidas, entre em contato pelo **Discord** ou pelo e-mail do professor. Bons estudos e divirta-se! 🐍