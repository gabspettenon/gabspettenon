{
   "success":true,
   "data":{
      "RecadAPI":{
         "pessoa":{
            "perfil":{
               "nome":"string(100)",
               "nome_social":"string(100)",
               "nascimento":"aaaa-mm-dd",
               "obito":"aaaa-mm-dd",
               "sexo":"string(6)",
               "estado_civil":"string(6)",
               "escolaridade":"string(6)",
               "nome_pai": "string(100)",
               "nome_mae": "string(100)",
               "obs1": "string",
               "obs2": "string"
            },
            "bio":{
               "pne":"string(6)",
               "etnia":"varchar(6)",
               "naturalidade":"string(64)",
               "nacionalidade":"string(20)"
            },
            "documentos":{
               "cpf":{
                  "cpf":"string(11)",
                  "cpf_dv":"string(2)",
                  "protocolo":"string(20)",
                  "data":"datetime"
               },
               "identidade":{
                  "identidade":"string(30)",
                  "emissao":"aaaa-mm-dd",
                  "emissor":"string(6)",
                  "uf":"string(2)"
               },
               "cnh":{
                  "cnh":"string(20)",
                  "validade":"aaaa-mm-dd",
                  "primeira_habilitacao":"aaaa-mm-dd",
                  "categoria":"string(2)",
                  "observacao":"string(100)",
                  "emissao":"aaaa-mm-dd",
                  "localidade":"string(64)"
               },
               "titulo_eleitor":{
                  "titulo_eleitor":"string(30)",
                  "secao":"string(3)",
                  "zona":"string(3)",
                  "emissao":"aaaa-mm-dd",
                  "localidade":"string(64)"
               }
            },
            "contatos":{
               "telefones":[
                  {
                     "tipo":"string(1)",
                     "ddi":55,
                     "ddd":81,
                     "prefixo":"string(5)",
                     "sufixo":"string(4)",
                     "verif_sms":0,
                     "verif_manual":1
                  }
               ],
               "emails":[
                  {
                     "email":"string(100)",
                     "verif":0
                  }
               ],
               "enderecos":[
                  {
                     "cep":"string(8)",
                     "tipo_logradouro":"string(30)",
                     "logradouro":"string(64)",
                     "numero":"string(10)",
                     "complemento":"string(64)",
                     "bairro":"string(64)",
                     "cidade":"string(64)"
                  }
               ]
            },
            "familia":{
               "string(6)":[
                  {
                     "cpf":"string(11)",
                     "nome":"string(100)",
                     "nome_social":"string(100)",
                     "nascimento":"aaaa-mm-dd",
                     "obito":"aaaa-mm-dd",
                     "sexo":"string(6)",
                     "estado_civil":"string(6)",
                     "escolaridade":"string(6)",
                     "data_inicio_dependencia": "aaaa-mm-dd",
                     "data_fim_dependencia": "aaaa-mm-dd",
                     "data_casamento_uniao": "aaaa-mm-dd",
                     "dependente_irrf": "string(1)",
                     "dependente_previdenciario": "string(1)",
                     "observacao": "string",
                     "avatar":{
                        "wa9tia":{
                           "public":[

                           ],
                           "private":[

                           ]
                        }
                     }
                  }
               ]
            },
            "avatar":{
               "wa9tia":{
                  "public":[
                     {
                        "foto_url":"string(255)"
                     }
                  ],
                  "private":[

                  ]
               }
            }
         },
         "servidor":{
            "matriculas":[
               {
                  "matricula":"string(10)",
                  "categoria": "string(30)",
                  "lotacao":"string(64)",
                  "cargo":"string(30)",
                  "admissao":"aaaa-mm-dd",
                  "pensionistas": [
                     {
                        "cpf_pensionista": "string(11)"
                     }
                  ],
                  "beneficio":{
                      "tipo": "string(20)",
                      "regra": "string(30)",
                      "data_concessao": "aaaa-mm-dd",
                      "paridade_ativos": "bool",
                      "extincao": "aaaa-mm-dd",
                      "observacao": "string"
                  }
               }
            ],
            "info_extras": {
               "numero_previdenciario": "int",
               "rpps_antigo": "string",
               "sequencial": "string",
               "matricula_pensionista": "string",
               "condicao_atual": "string(1)",
               "data_condicao_atual": "aaaa-mm-dd",
               "ipref_saude": "string(1)",
               "data_abono_permanencia": "aaaa-mm-dd"
            },
            "ctps":[
               {
                  "pf_ctps": "123123XX",
                  "pf_ctps_serie": "ABC1",
                  "pf_ctps_emissao": "2001-01-08",
                  "pf_ctps_uf": "PE"
               },
               {
                  "pf_ctps": "123123XX",
                  "pf_ctps_serie": "ABC1",
                  "pf_ctps_emissao": "2001-01-08",
                  "pf_ctps_uf": "PE"
               }
            ],
            "ctc":[
               {
                  "pf_ctc_num": "11111111111111",
                  "pf_ctc_emissor": "1111111111111111111111111",
                  "pf_ctc_cnpj_emissor": "53867473000157",
                  "pf_ctc_emissao": "1111-11-11"
               },
               {
                  "pf_ctc_num": "333333",
                  "pf_ctc_emissor": "1111111111111111111111111",
                  "pf_ctc_cnpj_emissor": "02422446000130",
                  "pf_ctc_emissao": "1111-11-11"
               }
            ]
         },
         "biometria":{
            "facial":{

            },
            "digital":{

            }
         },
         "avaliacao":{
            "selecionado":5
         },
         "validacao":{
            "protocolo":"string(64)",
            "emissao":"datetime"
         },
         "docs":{
            "string(6)":[
               {
                  "file_url":"string(255)"
               }
            ]
         },
         "elapsed_time_ms":1.234
      }
   }
}
