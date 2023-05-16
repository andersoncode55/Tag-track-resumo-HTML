# Tag track HTML
A tag track é uma tag HTML utilizada para adicionar legendas, descrições de áudio ou transcrições de vídeo a elementos de mídia, como audio e video. Essa tag permite fornecer suporte para legendas ou transcrições em diferentes idiomas, facilitando a acessibilidade e a compreensão do conteúdo multimídia.

# Sintaxe básica
A sintaxe básica para a tag track é a seguinte:
![Capturar_2023_05_16_15_50_18_255](https://github.com/andersoncode55/Tag-track-resumo-HTML/assets/61977421/3daaac3e-4e3c-46b2-91fe-022faed19753)

Nesse exemplo, temos um elemento video com um atributo controls para exibir controles de reprodução. A tag source é usada para especificar a origem do arquivo de vídeo, enquanto a tag track é usada para especificar o arquivo de legenda.
<video controls>

<video controls>
  <source src="video.mp4" type="video/mp4">
  <track src="legenda.vtt" kind="subtitles" srclang="pt" label="Português">
</video>

 # Atributos da tag <track>
A tag track possui vários atributos que podem ser utilizados para controlar o comportamento e as características das legendas. Alguns dos atributos mais comuns incluem:
  
<ul>
	<li>src: Especifica o caminho do arquivo de legenda.</li>
	<li>kind: Define o tipo de legenda. Os valores podem ser "subtitles" (legendas), "captions" (legendas descritivas), "descriptions" (descrições), "chapters" (capítulos) ou "metadata" (metadados).</li>
	<li>srclang: Especifica o idioma da legenda usando o código ISO 639-1.</li>
	<li>label: Define o rótulo ou nome da legenda, que será exibido nos controles do player de vídeo.</li>
</ul>
  
  
  
  # Suporte a navegadores
  É importante observar que nem todos os navegadores possuem suporte completo para a tag track. Alguns navegadores podem não renderizar as legendas corretamente ou não oferecer suporte a determinados recursos, como múltiplas faixas de legenda. É sempre recomendável verificar a compatibilidade dos navegadores de destino antes de usar a tag track.


  # Conclusão
  A tag track HTML é uma ferramenta poderosa para adicionar legendas, descrições de áudio ou transcrições de vídeo a elementos de mídia em páginas da web. Ao utilizar essa tag, você pode melhorar a acessibilidade e a experiência do usuário, garantindo que seu conteúdo multimídia seja compreensível para todos. Certifique-se de entender os atributos e as melhores práticas ao utilizar a tag track e verifique a compatibilidade dos navegadores para oferecer uma experiência consistente para seus usuários.




