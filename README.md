# Simulado das Regras IBJJF

Aplicação web para treinar faltas e cenários de arbitragem da IBJJF. O projeto oferece simulados dinâmicos com múltiplos modos, estatísticas persistentes e um painel completo para acompanhar seu progresso.

## 🔗 Acesso rápido
- Versão hospedada no GitHub Pages: [https://hbtmarc.github.io/simuladoibjjf](https://hbtmarc.github.io/simuladoibjjf)

## ✨ Principais recursos
- **Simulados configuráveis**: modos Geral, Faixa Branca, Faixa Preta e Corrigir Erros.
- **Banco com +100 questões**: perguntas categorizadas por dificuldade, tags e justificativas.
- **Estatísticas persistentes**: histórico salvo em `localStorage` com acertos, média e último desempenho.
- **Painel de fraquezas**: identifica as tags com mais erros e sugere os próximos estudos.
- **Revisão pós-prova**: lista todas as questões incorretas e permite iniciar um simulado focado nelas.
- **Interface responsiva**: layout otimizado para desktop e mobile com visual limpo e sem rolagem horizontal.

## 🛠️ Tecnologias utilizadas
- HTML5 sem build-step
- Tailwind CSS via CDN
- JavaScript vanilla com `localStorage`
- Font Awesome + Google Fonts

## ▶️ Como usar localmente
1. Clone ou baixe o repositório:
	```bash
	git clone https://github.com/hbtmarc/simuladoibjjf.git
	```
2. Abra o arquivo `index.html` diretamente no navegador (não há dependências extras).
3. Opcional: sirva com um servidor estático para testar em múltiplos dispositivos.

## 🤝 Contribuições
Sinta-se à vontade para abrir **Issues** ou enviar **Pull Requests** com novas perguntas, melhorias de UI ou correções nas regras. Apenas mantenha o padrão das questões (id, texto, opções, tag, nível e rationale).

---
Projeto mantido por @hbtmarc — sugestões e feedbacks são sempre bem-vindos.
