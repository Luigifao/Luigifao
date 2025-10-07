## Olá! 👋

Bem-vindo(a) ao meu perfil. Aqui você encontra um resumo das linguagens e frameworks com que eu trabalho, exemplos mínimos de código e um gráfico que mostra meus commits ao longo do tempo.

---

<!-- Badges -->

[![Profile views](https://komarev.com/ghpvc/?username=Luigifao&color=blue)](https://github.com/Luigifao)
[![GitHub followers](https://img.shields.io/github/followers/Luigifao?label=Seguidores&style=social)](https://github.com/Luigifao)
[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=Luigifao&layout=compact&theme=radical)](https://github.com/Luigifao)

---

## Sobre mim

- Nome: Luigifao (substitua pelo seu nome/username se desejar)
- Área: Desenvolvimento de software — front-end, back-end e automação
- Foco: código limpo, boas práticas e aprendizado contínuo

## Tecnologias e frameworks

Abaixo estão exemplos das linguagens e frameworks que uso frequentemente. Se quiser que eu adicione ou remova itens, diga quais são.

- 💻 JavaScript / TypeScript (Node.js, React)
- 🐍 Python (Flask, FastAPI)
- ☕ Java (Spring Boot, JWT)
- ⚛️ React / Next.js
- 🧰 Docker
- 🌐 HTML / CSS / SASS
- 🗄️ SQL / NoSQL
- 🔧 Git, CI/CD
---

- 🦋 Flutter (Dart) — mobile, web e desktop

---

## Trechos de código (exemplos rápidos)

JavaScript (Node.js) — servidor mínimo:

```javascript
// server.js
const http = require('http');

const server = http.createServer((req, res) => {
	res.writeHead(200, { 'Content-Type': 'text/plain' });
	res.end('Olá, mundo!');
});

server.listen(3000, () => console.log('Servidor na porta 3000'));
```

TypeScript (React) — componente funcional:

```tsx
// Hello.tsx
import React from 'react';

type Props = { name: string };

export default function Hello({ name }: Props) {
	return <h1>Olá, {name}!</h1>;
}
```

Python (FastAPI) — rota simples:

```python
# app.py
from fastapi import FastAPI

app = FastAPI()

@app.get('/')
def read_root():
		return {'message': 'Olá, mundo!'}
```

HTML/CSS — layout mínimo:

```html
<!-- index.html -->
<html>
	<head>
		<meta charset="utf-8" />
		<title>Exemplo</title>
		<style>body{font-family:Inter,system-ui,Arial;padding:2rem}</style>
	</head>
	<body>
		<h1>Olá, mundo!</h1>
	</body>
</html>
```

Flutter (Dart) — app mínimo:

```dart
// lib/main.dart
import 'package:flutter/material.dart';

void main() => runApp(const MyApp());

class MyApp extends StatelessWidget {
	const MyApp({super.key});

	@override
	Widget build(BuildContext context) {
		return MaterialApp(
			title: 'Exemplo Flutter',
			home: const Scaffold(
				body: Center(child: Text('Olá, Flutter!')),
			),
		);
	}
}
```



## Gráfico de commits ao longo do tempo

Segue um gráfico gerado dinamicamente mostrando a atividade de commits do usuário GitHub. Se o seu username é diferente de `Luigifao`, edite as URLs abaixo trocando `Luigifao` pelo seu username.

![Graphs of my commits over time](https://activity-graph.herokuapp.com/graph?username=Luigifao&theme=react-dark&area=true)

Alternativas:

- Cartão de estatísticas do GitHub:

![GitHub stats](https://github-readme-stats.vercel.app/api?username=Luigifao&show_icons=true&theme=radical)

---

## Como personalizar

1. Para mudar o username do gráfico e dos badges, substitua `Luigifao` nas URLs acima pelo seu username GitHub.
2. Para ajustar as linguagens/frameworks listadas, edite a seção "Tecnologias e frameworks".
3. Se quiser um gráfico local (SVG gerado por você), posso adicionar um script ou instruções para gerar um SVG a partir dos commits do git usando ferramentas locais.

Exemplo rápido de alteração de username (no Markdown):

```md
![Graphs](https://activity-graph.herokuapp.com/graph?username=SEU_USERNAME&theme=react-dark&area=true)
```

---

## Contato

- GitHub: https://github.com/Luigifao 
- E-mail: luigifao3@gmail.com
- Instagram: https://www.instagram.com/luig_itech?igsh=MWRzc2xvbjF6eHc4dg%253D%253D&utm_source=qr

