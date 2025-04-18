- Instalação fácil do wireguard usando servidores cloudflare warp em servidores vps 

- Evita bloqueio de IP em apps e outras coisas a mais

# Notas

- Informe o ip publico da vps
- Gere uma private key e uma public key

# Comando de instação

```bash
bash <(curl -sL https://github.com/zshroot70/wireguardflarevps/raw/refs/heads/main/wg)
```

**Não me resposabilizo por vps que não instala corretamente**

# Updates
- Suporte a IPv6 removido
- Agora usa o ip do engage.cloudflareclient.com pra evitar problemas em vps como qnax e akamai (Caso quiser editar: nano /etc/wireguard/wg0.conf e coloque o dominio ao invés do ip)
