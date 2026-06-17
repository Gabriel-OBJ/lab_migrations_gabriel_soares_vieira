# Lab Migrations Laravel
** Aluno :** Gabriel Soares Vieira
** Disciplina :** Programação WEB 1
** Professor :** Renato William R . de Souza
** Semestre :** 2026.1
## Como executar
‘‘‘ bash
git clone https :// github . com / SEU_USUARIO / lab_migrations_SEU_NOME . git
cd lab_migrations_SEU_NOME / lab_migrations
cp . env . example . env
# Editar . env com as credenciais do banco
composer install
php artisan key : generate
php artisan migrate
‘‘‘
## Atividades
| Atividade | Branch | Status |
| --- | --- | --- |
| Atividade 1 - Preparação do Ambiente 

 | atividade/01-ambiente 

 | Concluído |
| Atividade 2 - Primeira Migration 

 | atividade/02-primeira-migration 

 | Concluído |
| Atividade 3 - Tipos de Dados 

 | atividade/03-tipos-de-dados 

 | Concluído |
| Atividade 4 - Chave Estrangeira Simples 

 | atividade/04-chave-estrangeira 

 | Concluído |
| Atividade 5 - Uso do foreignId 

 | atividade/05-foreignid 

 | Concluído |
| Atividade 6 - Regras de Exclusão 

 | atividade/06-regras-exclusao 

 | Concluído |
| Atividade 7 - Alteração de Tabela 

 | atividade/07-alteracao-tabela 

 | Concluído |
| Atividade 8 - Status das Migrations 

 | atividade/08-status-migrations 

 | Concluído |
| Atividade 9 - Relacionamento Completo 1:N 

 | atividade/09-relacionamentoin- 

 | Concluído |
| Atividade 10 - Diagnóstico de Erros 

 | atividade/10-diagnostico-erros 

 | Concluído |
| Prática 1 - Sistema de Biblioteca 

 | pratica/01-biblioteca 

 | Concluído |
| Prática 2 - Sistema Acadêmico 

 | pratica/02-sistema-academico 

 | Concluído |
| Prática Avançada - Gestão de Projetos 

 | pratica/03-gestao-projetos 

 | Concluído |

## Status Final das Migrations (`lab_migrations`)

```text
 Migration name ............................................................................ Batch / Status 
 0001_01_01_000000_create_users_table ............................................................ [1] Ran 
 0001_01_01_000001_create_cache_table ............................................................ [1] Ran 
 0001_01_01_000002_create_jobs_table ............................................................. [1] Ran 
 2026_06_17_021155_create_clientes_table ......................................................... [2] Ran 
 2026_06_17_022136_create_produtos_table ......................................................... [3] Ran 
 2026_06_17_023034_create_categorias_table ....................................................... [4] Ran 
 2026_06_17_023038_add_categoria_id_to_produtos_table ............................................ [4] Ran 
 2026_06_17_023235_refactor_categoria_id_in_produtos_table ....................................... [5] Ran 
 2026_06_17_023617_add_cascade_to_categoria_id_in_produtos_table ................................. [6] Ran 
 2026_06_17_024126_add_descricao_to_produtos_table ............................................... [6] Ran 
 2026_06_17_024753_create_pedidos_table .......................................................... [7] Ran 
 2026_06_17_024757_create_itens_pedido_table ..................................................... [7] Ran 
 2026_06_17_025109_create_pedidos_items_table .................................................... [8] Ran 
 2026_06_17_030219_create_cursos_table ........................................................... [9] Ran 
 2026_06_17_030225_create_alunos_table ........................................................... [9] Ran 
 2026_06_17_030231_create_matriculas_table ....................................................... [9] Ran 
```