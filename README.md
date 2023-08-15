# ksql-panda-debizium

Após dar o pull, só meter o clássic "docker compose up";
E para brincar com o ksql é só rodar: docker exec -it ksqldb-cli ksql http://ksqldb-server:8088

Outro ponto:
Para criar o conector é só copiar o colar o json que está aí no root do projeto "mongo-connect-config.json"

No redpanda vá em connectors e clique para criar um novo conector mongo. Ele irá te jogar para uma página onde vc deveria preencher alguns, campos. Você pode dar next e ele irá te mostrar o json gerado a partir daqueles campos, lá é só trocar o que está lá pelo o que está no arquivo acima 

Bom divertimento e bons estudos!!