# Repositório de Imagens para Teste de Reconhecimento de Caracteres no Azure

Este repositório contém imagens utilizadas para testar e validar o reconhecimento de caracteres utilizando os serviços de visão computacional do Azure. As imagens estão organizadas em diretórios específicos, e os resultados das análises são armazenados separadamente para fácil consulta e avaliação.

## Estrutura do Repositório

```
📂 imagens/
   ├──📁 documentos/         # Imagens de documentos variados
   ├──📁 placas/             # Imagens de placas de rua, veículos, etc.
   ├──📁 captchas/           # Imagens com desafios de captcha
   ├──📁 manuscritos/        # Imagens de textos manuscritos
📂 resultados/
   ├──📁 documentos/         # Resultados da análise de documentos
   ├──📁 placas/             # Resultados da análise de placas
   ├──📁 captchas/           # Resultados da análise de captchas
   ├──📁 manuscritos/        # Resultados da análise de textos manuscritos
```

## Como Utilizar

1. **Upload de Imagens**: Adicione novas imagens nos diretórios correspondentes dentro da pasta `imagens/`.
2. **Processamento no Azure**: Utilize os serviços de OCR do Azure para analisar as imagens.
3. **Armazenamento de Resultados**: Salve os arquivos de saída (JSON, TXT, ou outro formato adequado) na pasta `resultados/`, respeitando a estrutura de diretórios.

## Tecnologias Utilizadas
- **Azure Cognitive Services - Computer Vision**

## Contribuição
Se deseja contribuir com este repositório, siga os passos:
1. Faça um fork do projeto.
2. Crie uma branch (`git checkout -b minha-feature`).
3. Faça commit das suas alterações (`git commit -m 'Adicionando nova imagem para teste'`).
4. Envie para o branch principal (`git push origin minha-feature`).
5. Abra um Pull Request.

## Contato
Caso tenha dúvidas ou sugestões, sinta-se à vontade para abrir uma issue ou entrar em contato.

---

Este repositório tem como objetivo facilitar o desenvolvimento e aprimoramento de modelos de OCR utilizando imagens reais e estruturadas para avaliação da performance dos algoritmos.
