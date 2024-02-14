# App 

GymPass style app.

## RFs (Requisitos funcionais)

- [ ] Deve ser possível se cadastrar;
- [ ] Deve ser possível se autenticar;
- [ ] Deve ser possível obter os perfil de um usuário logado;
- [ ] Deve ser possível obter o número de check-ins realizados pelo usuário logado;
- [ ] Deve ser possível o usuário obter seu histórico de check-ins;
- [ ] Deve ser possível o usuário buscar academias próximas;
- [ ] Deve ser possível o usuário buscar academias pelo nome;
- [ ] Deve ser possível o usuário realizar check-in em uma academia;
- [ ] Deve ser possível válidar o check-in de um usuário;
- [ ] Deve ser possível cadastrar uma academia;

## RNs (Regras de Negócio)

- [ ] O usuário não deve poder se cadastrar com um e-mail duplicado;
- [ ] O usuário não pode fazer 2 check-ins no mesmo dia;
- [ ] O usuário não pode fazer check-in se não estiver a pelo menos 100m da academia;
- [ ] O check-in só pode ser válidado até 20 minutos após criado;
- [ ] O check-in só pode ser válidado por administradores;
- [ ] A academia só pode ser cadastrada por administradores;

## RNFs (Requisitos não funcionais)

- [ ] A senha do usuário presia estar criptografada;
- [ ] Os dados da apliação precisam estar persistidos em um banco PostgresSQL
- [ ] Todas as listas de dados precisam estar paginadas com 20 itens por página
- [ ] O usuário deve ser identificado por um JWT