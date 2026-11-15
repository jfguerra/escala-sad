# Escala SAD

Protótipo de planeamento semanal para um Serviço de Apoio Domiciliário.

## Testar

Descarrega o ZIP em **Code → Download ZIP**, extrai a pasta e abre o terminal nessa pasta. Com Python 3, executa:

```sh
python3 -m http.server 8765 --bind 127.0.0.1
```

Abre [http://127.0.0.1:8765/](http://127.0.0.1:8765/) no navegador. Usa **Semana seguinte** para experimentar as folgas automáticas e as vagas na escala. Podes preencher uma vaga, trocar duas pessoas e alterar o apoio ao sábado na área **Rotas**.

A versão de teste começa com nomes de equipa fictícios e 30 utentes de exemplo. As alterações ficam no navegador de cada pessoa e podem ser exportadas por **Cópia de segurança**.
