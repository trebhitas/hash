Este projeto implementa um Gerenciador de Tarefas em Java com foco em segurança, auditoria e uso de estruturas de dados, combinando boas práticas de programação orientada a objetos com conceitos de criptografia, pilhas e listas encadeadas.
O sistema permite o cadastro, remoção, listagem e salvamento de tarefas, com controle de usuário e autenticação via hash seguro de senha (SHA-256). Além disso, utiliza criptografia AES para proteger os dados gravados em arquivo, garantindo confidencialidade e integridade.

Sistema de segurança implementado:
Hash de senha (SHA-256 + salt) — impede que senhas fiquem armazenadas em texto puro
Criptografia AES — protege o conteúdo do arquivo de tarefas
Logs de auditoria — permitem rastrear ações realizadas no sistema

Estruturas de dados utilizado:
LinkedList - armazenamento dinâmico de tarefas
Stack - controle do histórico e operação de desfazer
Lista de Logs (LinkedList) - registro de auditoria do sistema


