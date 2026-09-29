# Modelagem de Banco de Dados – Recursos Humanos

### Professora Ellen Martins Lopes da Silva

## 📚 Sobre o Projeto

Este projeto apresenta um modelo conceitual de banco de dados para um sistema de Recursos Humanos (RH), com entidades, atributos, relacionamentos e cardinalidades.

## 🗂️ Entidades e Atributos

### 1. Área de Atuação

* `id_area`
* `cod_centro_custo`
* `endereco`
* `cod_alfa_num_area`
* `nome_area`

### 2. Empregado

* `id_cod_alfa_num_empregado`
* `nome`
* `endereco`
* `documentos`
* `cod_lotacao`
* `cod_nv_salarial`
* `cod_cargo`

### 3. Dependente

* `id_cod_empregado`
* `nome`
* `data_nascimento`
* `tipo_identidade`
* `num_identidade`
* `tipo_parentesco`

### 4. Cargo

* `id_cod_alfa_num_cargo`
* `nome_cargo`
* `nv_hierarquico`
* `cod_LR`
* `ind_nv_gerencial`
* `cod_ref_salarial_min`
* `cod_ref_salarial_max`

### 5. Referência Salarial

* `id_cod_alfa_num_ref_salarial`
* `valor_salario_ref`
* `data_inicio_vig_ref`
* `data_final_vig_ref`

## 🔗 Relacionamentos

* **Área de Atuação e Empregado:** representa a área em que o empregado atua.
* **Empregado e Dependente:** representa os dependentes vinculados a um empregado.
* **Empregado e Cargo:** representa o cargo ocupado pelo empregado.
* **Cargo e Referência Salarial:** relaciona os cargos às referências salariais.

## 🎯 Objetivo

Organizar os dados dos empregados, suas áreas de atuação, dependentes, cargos e referências salariais, facilitando a representação das informações de um sistema de Recursos Humanos.

## 🛠️ Conceitos Utilizados

* Modelagem conceitual de banco de dados
* Entidades e atributos
* Relacionamentos
* Cardinalidade

---
