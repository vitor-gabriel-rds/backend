# =============================================
# VARIÁVEIS DE AMBIENTE - COPIE ESTE ARQUIVO
# Renomeie para .env e preencha com seus dados
# =============================================

# URL de conexão com o MongoDB Atlas
# Obtenha em: https://cloud.mongodb.com -> Connect -> Drivers
MONGODB_URI=mongodb+srv://vitor:vitor@cluster0.0ficzga.mongodb.net/?appName=Cluster0

# Chave secreta para assinar os tokens JWT
# Use uma string longa e aleatória (ex: gerada em https://randomkeygen.com/)
JWT_SECRET=41f0e50775f7ffece068d676

# Tempo de expiração do token JWT (1d = 1 dia, 7d = 7 dias)
JWT_EXPIRES_IN=7d

# Porta em que o servidor vai rodar localmente
PORT=3001

# ---- Configurações de E-mail (para "Esqueci a senha") ----
# Use Gmail com "Senhas de app" ou outro provedor SMTP
EMAIL_HOST=smtp.gmail.com
EMAIL_PORT=587
EMAIL_USER=viarvellos@gmail.com
EMAIL_PASS=vrtoemwnwjnrcypk

# URL do frontend (usado nos links do e-mail de recuperação)
FRONTEND_URL=http://localhost:5173
