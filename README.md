# fullcycle-kibana-beat-elastic
Exemplo de uso do beat com uma imagem nginx no docker enviando para o kibana (elastic)

### Requisitos

Estar habilidatado a quantidade de memória minima para rodar o elastic de 2,6 GB 

Error ao vai ocorrer ao não estar com esse processo 


````bash
max virtual memory areas vm.max_map_count [65530] is too low, increase to at least [262144]
````

Para habilitar entrar dentro do WSL e executar o comando:

````bash
  $ sysctl -w vm.max_map_count=262144
  $ wsl --shutdown
````
