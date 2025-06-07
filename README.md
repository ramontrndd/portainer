##  Pré-requisitos  📝

Você deve criar 6 subdominios do tipo 'A' na Cloudflare

<p>portainer</p>
<p>www.portainer</p>
<p>traefik</p>
<p>www.traefik</p>
<p>edge</p>
<p>www.edge</p>

<img src="https://raw.githubusercontent.com/ramontrndd/portainer/refs/heads/images/image/apontamento.png" />
<hr>
<h5> ⚠️⚠️⚠️ TODOS OS SUBDOMINIOS DEVEM APONTAR PARA O IP DA SUA VPS ⚠️⚠️⚠️ </h5>


## 🖥️💿 Instalação

<h6>Copie e cole no Terminal da sua VPS:</h6>


```
sudo apt update && sudo apt install -y git && git clone https://github.com/ramontrndd/portainer.git && cd portainer && sudo chmod +x install.sh && ./install.sh
```

#### PREENCHA COM AS INFORMAÇÕES SOLICITADAS NO SCRIPT E ACESSE O SEU PORTAINER COM CERTIFICADO SSL USANDO TRAEFIK 

<hr>
