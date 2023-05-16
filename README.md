# Resolution "trilha-net-banco-de-dados-desafio"

Reesolução do desafio de Banco de dados do curso Formação .NET Developer da plataforma DIO.</br>


## Desafio 1
### Código para a resolução;
* 1 - </br>
SELECT Nome, Ano FROM Filmes</br>
</br>![desafio 1](https://github.com/CelioSouzaDv/Resolution-trilha-net-banco-de-dados-desafio/assets/127158626/a83cf488-06b0-4cbd-be14-1be5f833ba97)</br>

## Desafio 2
### Código para a resolução;
* 2 - </br>
SELECT Nome, Ano, Duracao FROM Filmes</br>
ORDER BY Ano</br>
</br>![d2](https://github.com/CelioSouzaDv/Resolution-trilha-net-banco-de-dados-desafio/assets/127158626/32c4aa54-81d4-43e8-9aa7-c9b35fc4a072)</br>

## Desafio 3
### Código para a resolução;
* 3 - </br>
SELECT Nome, Ano, Duracao FROM Filmes</br>
WHERE Nome = 'De volta para o Futuro'</br>
</br>![d3](https://github.com/CelioSouzaDv/Resolution-trilha-net-banco-de-dados-desafio/assets/127158626/5ce01656-96e4-43b2-b9e8-23cde0bc3b32)</br>

## Desafio 4
### Código para a resolução;
* 4 - </br>
SELECT Nome, Ano, Duracao FROM Filmes</br>
WHERE Ano = 1997</br>
</br>![d4](https://github.com/CelioSouzaDv/Resolution-trilha-net-banco-de-dados-desafio/assets/127158626/e007ea87-7e1f-4a4e-8899-7b58dd489a74)</br>

## Desafio 5
### Código para a resolução;
* 5 - </br>
SELECT Nome, Ano, Duracao FROM Filmes</br>
WHERE Ano > 2000</br>
</br>![d5](https://github.com/CelioSouzaDv/Resolution-trilha-net-banco-de-dados-desafio/assets/127158626/0ba140e0-9419-4511-8329-a94143edf719)</br>

## Desafio 6
### Código para a resolução;
* 6 - </br>
SELECT Nome, Ano, Duracao FROM Filmes</br>
WHERE Duracao >100 AND Duracao <150</br>
ORDER BY Duracao</br></br>
</br>![d6](https://github.com/CelioSouzaDv/Resolution-trilha-net-banco-de-dados-desafio/assets/127158626/b7f70a72-c2d2-41d3-9f8a-3d42ea59eeb0)</br>

## Desafio 7
### Código para a resolução;
* 7 - </br>
SELECT Ano, COUNT(Ano) Quantidade FROM Filmes</br>
GROUP BY Ano ORDER BY Quantidade DESC</br>
</br>![d7](https://github.com/CelioSouzaDv/Resolution-trilha-net-banco-de-dados-desafio/assets/127158626/72c5a710-d91b-44df-bff7-96bad8d80d3b)</br>

## Desafio 8
### Código para a resolução;
* 8 - </br>
SELECT * FROM Atores</br>
WHERE Genero = 'M'</br>
</br> ![d8](https://github.com/CelioSouzaDv/Resolution-trilha-net-banco-de-dados-desafio/assets/127158626/04845c39-12d3-4ef1-862b-10795992d354)</br>

## Desafio 9
### Código para a resolução;
* 9 - </br>
SELECT * FROM Atores</br>
WHERE Genero = 'F'</br>
</br>![d9](https://github.com/CelioSouzaDv/Resolution-trilha-net-banco-de-dados-desafio/assets/127158626/c9910ab8-e700-4d77-9544-e25ff4b6a151)</br>

## Desafio 10
### Código para a resolução;
* 10 - </br>
SELECT </br>
F.Nome,</br>
G.Genero</br>

FROM Filmes F</br>
INNER JOIN FilmesGenero FG on F.Id = FG.IdFilme</br>
INNER JOIN Generos G on FG.IdGenero = G.Id </br>

</br>![d10](https://github.com/CelioSouzaDv/Resolution-trilha-net-banco-de-dados-desafio/assets/127158626/a57d013e-664c-4914-a715-f10cbed5df06)</br>

## Desafio 11
### Código para a resolução;
* 11 - </br>
SELECT</br>
F.Nome,</br>
G.Genero</br>

FROM Filmes F</br>
INNER JOIN FilmesGenero FG on F.Id = FG.IdFilme</br>
INNER JOIN Generos G on FG.IdGenero = G.Id</br>
WHERE Genero = 'Mistério'</br>
</br>
![d11](https://github.com/CelioSouzaDv/Resolution-trilha-net-banco-de-dados-desafio/assets/127158626/7970e050-99c2-4aff-a199-c8c5e85f2ecf)
</br>

## Desafio 12
### Código para a resolução;
* 12 - </br>
SELECT</br>
Filmes.Nome,</br>
Atores.PrimeiroNome,</br>
Atores.UltimoNome,</br>
ElencoFilme.Papel</br>
FROM Filmes</br>
INNER JOIN ElencoFilme on Filmes.Id = ElencoFilme.IdFilme</br>
INNER JOIN Atores on ElencoFilme.IdAtor = Atores.Id</br>
</br>![d12](https://github.com/CelioSouzaDv/Resolution-trilha-net-banco-de-dados-desafio/assets/127158626/3966a897-aaed-46b3-9678-b93835eec99e)</br>









