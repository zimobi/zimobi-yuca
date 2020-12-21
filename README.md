# Fields

| Field                 | Name                               | Type    | Rules    | Example                                                        |
| :-------------------- | :--------------------------------- | :------ | :------- | :------------------------------------------------------------- |
| Rua                   | street                             | string  | required | `"Avenida Paulista"`                                           |
| Numero                | number                             | integer | required | `123`                                                          |
| Complemento           | complement                         | string  | optional |                                                                |
| Bairro                | neighbourhood                      | string  | required | `"Jardim Paulista"`                                            |
| Cidade                | city                               | string  | required | `"São Paulo"`                                                  |
| Estado (Sigla)        | state                              | string  | required | `"SP"`                                                         |
| CEP                   | postal_code                        | string  | required | `"12345-000"`                                                  |
| Tipo do Imóvel        | property_type                      | string  | required | `"flat"`                                                       |
| Tipo do Aluguel       | rental_type                        | string  | required | `"residential"`                                                |
| Área Util             | usable_floor_area_in_square_meters | integer | required | `85`                                                           |
| Andar                 | floor                              | integer | required | `3`                                                            |
| Quartos               | number_of_rooms                    | integer | required | `2`                                                            |
| Suites                | number_of_suites                   | integer | required |                                                                |
| Vagas de Garagem      | number_of_parking_spots            | integer | required |                                                                |
| Titulo do Anúncio     | title                              | string  | required |                                                                |
| Descrição do Anúncio  | description                        | string  | required |                                                                |
| Valor do Aluguel      | rental_price_in_cents              | integer | required | `210000` -> R$ 2.100,00                                        |
| Valor do Condominio   | condo_fee_in_cents                 | integer | optional | `50000` -> R$ 500,00                                           |
| Valor do Iptu         | iptu_price_in_cents                | integer | optional | `25000` -> R$ 250,00                                           |
| Valor Total           | total_price_in_cents               | integer | required | `285000`-> R$ 2.850,00 (rental_price + iptu_price + condo_fee) |
| Mobilia               | furnish_type                       | string  | required | `"no"`                                                         |
| Aceita pets           | allow_pets                         | boolean | optional | `true`                                                         |
| Area de serviço       | service_area                       | boolean | optional | `false`                                                        |
| Armário no quarto     | room_cabinet                       | boolean | optional | `false`                                                        |
| Armário na cozinha    | kitchen_cabinet                    | boolean | optional | `false`                                                        |
| Ar condicionado       | air_conditioner                    | boolean | optional | `false`                                                        |
| Churrasqueira         | barbecue_grill                     | boolean | optional | `false`                                                        |
| Varanda               | balcony                            | boolean | optional | `false`                                                        |
| Piscina particular    | private_pool                       | boolean | optional | `false`                                                        |
| Quarto de serviço     | service_room                       | boolean | optional | `false`                                                        |
| Condominio fechado    | private_condominium                | boolean | optional | `false`                                                        |
| Elevador              | elevator                           | boolean | optional | `false`                                                        |
| Segurança 24h         | security_24h                       | boolean | optional | `false`                                                        |
| Portaria              | concierge                          | boolean | optional | `false`                                                        |
| Salão de festas       | party_room                         | boolean | optional | `false`                                                        |
| Piscina no condomínio | shared_pool                        | boolean | optional | `false`                                                        |
| Academia              | shared_gym                         | boolean | optional | `false`                                                        |
| Observações           | observations                       | boolean | optional | `false`                                                        |

# Options for Fields

### property_type
flat apartment studio kitnet

---
### rental_type
residential commercial

---
### furnish_type
no yes semi
