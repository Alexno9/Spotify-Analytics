# Spotify Analytics

No notebook em Python é feita uma comunicação com a API do Spotify para buscar todas as playlists salvas na conta do usuário.
A API traz como resposta as playlists no formato .JSON e para cada playlist, traz arquivos em .CSV retratando diversas métricas relacionadas a cada música contida nas playlists.

Arquivos Orange Canvas:
  
  SpotifyFeatures - União de todos os arquivos de features das musicas em cada playlist;
  
  SpotifyPlaylists - União de todas as playlists em um arquivo;
  
  MergePlaylistFeatures - União dos arquivos de feature das musicas e o arquivo de playlists.
  
Com todos os arquivos unificados, é possível importa-los para uma ferramenta de visualização como Tableau ou Metabase, afim de tirar conclusões a respeito dos gostos musicais do usuário.
