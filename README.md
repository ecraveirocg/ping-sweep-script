# Ping Sweep Script

## Descrição
Este script realiza um **Ping Sweep** em uma faixa de endereços IP para identificar quais estão ativos na rede. Ele pode ser utilizado para testes de conectividade, análise de redes ou auditorias de segurança.

## Funcionalidades
- Varredura de uma faixa de endereços IP
- Exibe quais hosts estão ativos
- Relatório simples e rápido
- Suporte a diferentes sistemas operacionais

## Requisitos
- Python 3.x
- Biblioteca `subprocess`
- Permissões de administrador (em alguns sistemas operacionais)

## Como Usar
1. Clone este repositório:
   ```sh
   git clone https://github.com/seu-usuario/ping-sweep.git
   ```
2. Acesse a pasta do projeto:
   ```sh
   cd ping-sweep
   ```
3. Execute o script informando o intervalo de IPs:
   ```sh
   python3 ping_sweep.py 192.168.1.1 192.168.1.255
   ```

## Exemplo de Saída
```
[+] 192.168.1.1 está ativo
[+] 192.168.1.5 está ativo
[+] 192.168.1.10 está ativo
```

## Contribuição
Sinta-se à vontade para contribuir com melhorias, abrindo **Issues** ou enviando **Pull Requests**.

