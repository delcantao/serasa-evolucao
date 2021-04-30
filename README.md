#  <img src="https://www.thinkdata.com.br/wp-content/uploads/2021/03/logo-think-data.svg" width="40%">  
# Overview do desenvolvimento do sistema Serasa de consultas


### Consultas de distribuidor Serasa

- [x] Creditbureau
  - ✅ Integrado 
  - ✅ ![100%](https://progress-bar.dev/100) | Ambiente - Produção  
  - ✅ ![100%](https://progress-bar.dev/100) | Ambiente - Dev       
  - ✅ ![100%](https://progress-bar.dev/100) | Mapeado?  (igor) 
  - ✅ ![100%](https://progress-bar.dev/100) | Testado?  
- [ ] Prorede
  - ✅ ![100%](https://progress-bar.dev/100) | Integrado  
  - ✅ ![100%](https://progress-bar.dev/100) | Ambiente - Produção  
  - ✅ ![100%](https://progress-bar.dev/100) | Ambiente - Dev       
  - ✅ ![100%](https://progress-bar.dev/100) | Mapeado?  (lf) 
  - ❌ ![90%](https://progress-bar.dev/90) | Testado?  
- [ ] Crednet
  - ✅ ![100%](https://progress-bar.dev/100) | Integrado 
  - ✅ ![100%](https://progress-bar.dev/100) | Ambiente - Produção  
  - ✅ ![100%](https://progress-bar.dev/100) | Ambiente - Dev       
  - ✅ ![100%](https://progress-bar.dev/100) | Mapeado?  (bruno) 
  - ❌ ![50%](https://progress-bar.dev/50) | Testado?  
- [ ] Concentre
  - ✅ ![100%](https://progress-bar.dev/100) | Integrado 
  - ✅ ![100%](https://progress-bar.dev/100) | Ambiente - Produção  
  - ✅ ![100%](https://progress-bar.dev/100) | Ambiente - Dev       
  - ❌ ![90%](https://progress-bar.dev/90) | Mapeado?  (lf) 
  - ❌ ![0%](https://progress-bar.dev/0) | Testado?  
- [ ] Infomais
  - ✅ ![100%](https://progress-bar.dev/100) | Integrado  
  - ✅ ![100%](https://progress-bar.dev/100) | Ambiente - Produção  
  - ✅ ![100%](https://progress-bar.dev/100) | Ambiente - Dev       
  - ❌ ![0%](https://progress-bar.dev/0) |  Mapeado? (bruno)
  - ❌ ![0%](https://progress-bar.dev/0) | Testado? 
- [ ] Relato
  - ✅ ![100%](https://progress-bar.dev/100) | Integrado  
  - ✅ ![100%](https://progress-bar.dev/100) | Ambiente - Produção  
  - ✅ ![100%](https://progress-bar.dev/100) | Ambiente - Dev       
  - ❌ ![0%](https://progress-bar.dev/0) | Mapeado? (lf) 
  - ❌ ![0%](https://progress-bar.dev/0) | Testado? 

### Overview do desenvolvimento da Api Serasa

#### Entidades do banco de dados

- [x] Replicação 
  - ✅ ![100%](https://progress-bar.dev/100) | Projetado                     
  - ✅ ![100%](https://progress-bar.dev/100) |  Testes                        
- [x] Segurança 
  - ✅ ![100%](https://progress-bar.dev/100) | Criptografia de Senha         
  - ✅ ![100%](https://progress-bar.dev/100) | Testes                  
 
  - #### Processo de Autenticação do Site 
    - ![Auth process 1](https://github.com/delcantao/serasa-evolucao/blob/master/images/Auth%20process%20site.png)
  - ####  Processo de Autenticação da API
    - ![Auth process 2](https://github.com/delcantao/serasa-evolucao/blob/master/images/Auth%20process%20api.png)

- [x] Entity Frameworks
  - ✅ ![100%](https://progress-bar.dev/100) | [dbo].[Billet]                
  - ✅ ![100%](https://progress-bar.dev/100) | [dbo].[Card]                
  - ✅ ![100%](https://progress-bar.dev/100) | [dbo].[Client]                
  - ✅ ![100%](https://progress-bar.dev/100) | [dbo].[CustomPrices]                
  - ✅ ![100%](https://progress-bar.dev/100) | [dbo].[Error]                 
  - ✅ ![100%](https://progress-bar.dev/100) | [dbo].[Extract]                 
  - ✅ ![100%](https://progress-bar.dev/100) | [dbo].[ExtractSent]                 
  - ✅ ![100%](https://progress-bar.dev/100) | [dbo].[Plans]                 
  - ✅ ![100%](https://progress-bar.dev/100) | [dbo].[Prices]                
  - ✅ ![100%](https://progress-bar.dev/100) | [dbo].[Purchase]                
  - ✅ ![100%](https://progress-bar.dev/100) | [dbo].[Security]                
  - ✅ ![100%](https://progress-bar.dev/100) | [dbo].[Usage]                 
  - ✅ ![100%](https://progress-bar.dev/100) | [dbo].[User]                
  - ✅ ![100%](https://progress-bar.dev/100) | [dbo].[Voucher]                 

#### Middlewares de Segurança da Api

- [x] Autenticação
  - ✅ ![100%](https://progress-bar.dev/100) | Projetado                     
  - ✅ ![100%](https://progress-bar.dev/100) | Ligação com o banco de dados  
  - ✅ ![100%](https://progress-bar.dev/100) | Desenvolvimento               
  - ✅ ![100%](https://progress-bar.dev/100) |  Testes                        

- [ ] Autorização
  - ✅ ![100%](https://progress-bar.dev/100) |  Projetado                     
  - ✅ ![90%](https://progress-bar.dev/90) | Desenvolvimento               
  - ❌ ![0%](https://progress-bar.dev/0) |  Testes                        

#### Controllers de Serviços de Background da Api 

- [ ] Cadastro de Cliente
  - ✅ ![100%](https://progress-bar.dev/100) | Projetado                     
  - ✅ ![100%](https://progress-bar.dev/100) | Ligação com o banco de dados  
  - ❌ ![40%](https://progress-bar.dev/40) | Desenvolvimento               
  - ❌ ![100%](https://progress-bar.dev/100) | [get]  Listar Clientes        
  - ❌ ![100%](https://progress-bar.dev/100) | [post] Registrar Cliente      
  - ❌ ![0%](https://progress-bar.dev/0) | [patch] Atualizar Cliente     
  - ❌ ![0%](https://progress-bar.dev/0) | [delete] Excluir Cliente      
  - ❌ ![0%](https://progress-bar.dev/0) | Testes                        

- [ ] Cadastro de Usuários
  - ✅ ![100%](https://progress-bar.dev/100) | Projetado                     
  - ✅ ![100%](https://progress-bar.dev/100) | Ligação com o banco de dados  
  - ❌ ![40%](https://progress-bar.dev/40) | Desenvolvimento               
  - ❌ ![50%](https://progress-bar.dev/50) | [get]  Listar Usuários        
  - ❌ ![20%](https://progress-bar.dev/20) | [post] Registrar Usuário      
  - ❌ ![10%](https://progress-bar.dev/10) | [patch] Atualizar Usuário     
  - ❌ ![0%](https://progress-bar.dev/0) | [delete] Excluir Usuário      
  - ❌ ![0%](https://progress-bar.dev/0) | Testes                        

- [ ] Cadastro de Cartões
  - ❌ ![0%](https://progress-bar.dev/0) | Projetado                     
  - ✅ ![100%](https://progress-bar.dev/0) | Ligação com o banco de dados  
  - ❌ ![0%](https://progress-bar.dev/0) | [get]  Listar Cartões            
  - ❌ ![0%](https://progress-bar.dev/0) | [post] Salvar Cartão            
  - ❌ ![0%](https://progress-bar.dev/0) | Testes                        

- [ ] Geração de Boletos
  - ❌ ![0%](https://progress-bar.dev/0) | Projetado                     
  - ✅ ![100%](https://progress-bar.dev/0) | Ligação com o banco de dados  
  - ❌ ![0%](https://progress-bar.dev/0) | [get]  Listar Boletos            
  - ❌ ![0%](https://progress-bar.dev/0) | [post] Gerar Boleto            
  - ❌ ![0%](https://progress-bar.dev/0) | Testes                        

- [ ] Endpoint de Preços
  - ✅ ![100%](https://progress-bar.dev/100) | Projetado                     
  - ❌ ![0%](https://progress-bar.dev/0) | Ligação com o banco de dados  
  - ❌ ![0%](https://progress-bar.dev/0) | [get] Listar Preços            
  - ❌ ![0%](https://progress-bar.dev/0) | Testes                        
 
- [ ] Compras
  - ❌ ![0%](https://progress-bar.dev/0) | Projetado                       
  - ✅ ![100%](https://progress-bar.dev/0) | Ligação com o banco de dados    
  - ❌ ![0%](https://progress-bar.dev/0) | [get] Listar Compras            
  - ❌ ![0%](https://progress-bar.dev/0) |  [post] Registrar Compra         
  - ❌ ![0%](https://progress-bar.dev/0) | Testes                          
  
- [ ] Uso
  - ❌ ![0%](https://progress-bar.dev/0) | Projetado                                     
  - ✅ ![100%](https://progress-bar.dev/100) | Ligação com o banco de dados                  
  - ❌ ![0%](https://progress-bar.dev/0) |  [get] Listar Uso (Relatório)                  
  - ❌ ![0%](https://progress-bar.dev/0) | Testes                                        

- [ ] Erro
  - ❌ ![0%](https://progress-bar.dev/0) | Projetado                                     
  - ✅ ![100%](https://progress-bar.dev/100) | Ligação com o banco de dados                  
  - ❌ ![0%](https://progress-bar.dev/0) |  [post] Registrar Erro                         
  - ❌ ![0%](https://progress-bar.dev/0) | Testes                                        
 
- [ ] Cupons
  - ❌ ![0%](https://progress-bar.dev/0) | Projetado                                     
  - ✅ ![100%](https://progress-bar.dev/100) | Ligação com o banco de dados                  
  - ❌ ![0%](https://progress-bar.dev/0) | Testes                                        
  - ❌ ![0%](https://progress-bar.dev/0) |  [get] Listar Cupom                            
  - ❌ ![0%](https://progress-bar.dev/0) |  [post] Registrar Cupom                        
  - ❌ ![0%](https://progress-bar.dev/0) |  [delete] Excluir Cupom                        
  - ❌ ![0%](https://progress-bar.dev/0) |  [patch] Atualizar Cupom                        

#### Controllers de Serviços Expostos - (Consultas) 
- [ ] Consulta CPF
  - ✅ ![100%](https://progress-bar.dev/100) | Projetado                     
  - ✅ ![100%](https://progress-bar.dev/100) | Ligação com o banco de dados  
  - ✅ ![20%](https://progress-bar.dev/20) | Desenvolvimento               
  - ❌ ![0%](https://progress-bar.dev/0) | Testes                        

- [ ] Consulta CNPJ
  - ✅ ![100%](https://progress-bar.dev/100) | Projetado                     
  - ✅ ![100%](https://progress-bar.dev/100) | Ligação com o banco de dados  
  - ❌ ![20%](https://progress-bar.dev/20) | Desenvolvimento               
  - ❌ ![0%](https://progress-bar.dev/0) | Testes                        

- [ ] Monitoramento CNPJ
  - ❌ ![0%](https://progress-bar.dev/0) | Projetado                     
  - ✅ ![100%](https://progress-bar.dev/100) | Ligação com o banco de dados                  
  - ❌ ![0%](https://progress-bar.dev/0) | Desenvolvimento               
  - ❌ ![0%](https://progress-bar.dev/0) | Testes                        

- [ ] Cheques
  - ❌ ![0%](https://progress-bar.dev/0) | Projetado                     
  - ✅ ![100%](https://progress-bar.dev/100) | Ligação com o banco de dados                  
  - ❌ ![0%](https://progress-bar.dev/0) | Desenvolvimento               
  - ❌ ![0%](https://progress-bar.dev/0) | Testes                        

- [ ] Pendências
  - ❌ ![0%](https://progress-bar.dev/0) | Projetado                     
  - ✅ ![100%](https://progress-bar.dev/100) | Ligação com o banco de dados                  
  - ❌ ![0%](https://progress-bar.dev/0) | Desenvolvimento               
  - ❌ ![0%](https://progress-bar.dev/0) | Testes                        

- [ ] Negativação/Desnegativação
  - ❌ ![0%](https://progress-bar.dev/0) | Projetado                     
  - ✅ ![100%](https://progress-bar.dev/100) | Ligação com o banco de dados                  
  - ❌ ![0%](https://progress-bar.dev/0) | Desenvolvimento               
  - ❌ ![0%](https://progress-bar.dev/0) | Testes                        
  - ❌ ![0%](https://progress-bar.dev/0) |  [post] Registrar Negativação                        
  - ❌ ![0%](https://progress-bar.dev/0) |  [delete] Registrar Desnegativação                        

- [ ] Telefones por CPF/CNPJ
  - ❌ ![0%](https://progress-bar.dev/0) | Projetado                     
  - ✅ ![100%](https://progress-bar.dev/100) | Ligação com o banco de dados                  
  - ❌ ![0%](https://progress-bar.dev/0) | Desenvolvimento               
  - ❌ ![0%](https://progress-bar.dev/0) |  Testes                        

- [ ] Endereço por CPF/CNPJ
  - ❌ ![0%](https://progress-bar.dev/0) | Projetado                     
  - ✅ ![100%](https://progress-bar.dev/100) | Ligação com o banco de dados                  
  - ❌ ![0%](https://progress-bar.dev/0) | Desenvolvimento               
  - ❌ ![0%](https://progress-bar.dev/0) |  Testes                        

- [ ] Endereço por telefone
  - ❌ ![0%](https://progress-bar.dev/0) | Projetado                     
  - ✅ ![100%](https://progress-bar.dev/100) | Ligação com o banco de dados                  
  - ❌ ![0%](https://progress-bar.dev/0) | Desenvolvimento               
  - ❌ ![0%](https://progress-bar.dev/0) |  Testes                        
