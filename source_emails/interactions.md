## Interactions for Wakaru Source Data

### Definitions

+ `public result` refers to the result from the google form, submitted by an anonymous volunteer, which is designed to `loosely` mimic an email conversation between a customer and customer service representative
+ `private result` refers to the result from the google form, submitted by an approved source, which is designed to `closely` mimic a real conversation between a customer and customer service representative

### Interaction Pattern

Each form will have two messages:

+ First: customer's query
+ Second: company's response
  + for `good` responses, reasoning is expected  
  + For `bad` responses, excluding reasoning is a legitimate tactic for increasing negative tone

### Source Organization

Public results will be sorted into three categories upon receipt:

+ `denying_request_bad`
+ `denying_request_good`
+ `granting_request_good`

### Source Forms

#### Public result forms

###### Wait Time Queries
+ [wait_time_granting_request_good](https://docs.google.com/forms/d/e/1FAIpQLScrN67IPdkUv_HCQsrNt5OA9MAqXBdxlpV_7wTNH-bbh6OcVw/viewform)
+ [wait_time_denying_request_good](https://docs.google.com/forms/d/e/1FAIpQLSegBjxlyDbalSR8Mp56KwOAGxPDZUIorPCoyzNqsAexfnWiyA/viewform)
+ [wait_time_denying_request_bad](https://docs.google.com/forms/d/e/1FAIpQLSfvcDyT7WjE-XCUEZc1uWti9C164Uq-qc4vcgIr1T0ztz_ppQ/viewform)
###### Warranty Queries
+ [warranty_granting_request_good](https://docs.google.com/forms/d/e/1FAIpQLSf91Frgs0fGr5XYD2wHj1gzKaTWRObGPydHm_sS-UMgN3iQYQ/viewform)
+ [warranty_denying_request_good](https://docs.google.com/forms/d/e/1FAIpQLSfeF0wD6bRT2IT8zqyMVl1jf6fVfNZ0qgDEDxcwD1tEaLb-Og/viewform)
+ [warranty_denying_request_bad](https://docs.google.com/forms/d/e/1FAIpQLScl-QX2IaLG3-EZkCDtad238I-n9kov21G1CufpFvrmnQKrVw/viewform)

#### Private result forms

###### Surfboard Inventory Queries
+ [surfboard_inventory_granting_request_good](https://docs.google.com/forms/d/e/1FAIpQLSeqpH_KoPa_rebbqDp-NlFu5xODtJMGTiriCFA9idVaE7JiSQ/viewform)
+ [surfboard_inventory_denying_request_good](https://docs.google.com/forms/d/e/1FAIpQLScuCogyfMJhqIxdlJ_3yJRvhNZSPTjkg17IVP6nELxZBswIGQ/viewform)
+ [surfboard_inventory_denying_request_bad](https://docs.google.com/forms/d/e/1FAIpQLScJCVeolCzqM8ov8Lq1BOnFuK3omjeXKQ1Sh4_lLgtt5eNs9w/viewform)

###### Accessories Inventory Queries

+ [accessories_inventory_granting_request_good](https://docs.google.com/forms/d/e/1FAIpQLScWom1heXxXdFKZLwz_6PYwk-pyhb30LLdeM4qCnSNv4sA1hQ/viewform)
+ [accessories_inventory_denying_request_good](https://docs.google.com/forms/d/e/1FAIpQLSdaTJ8zTCF-PMeNwJArCte7oUGFzY_CqrgrHCy8CBQBpb8q2A/viewform)
+ [accessories_inventory_denying_request_bad](https://docs.google.com/forms/d/e/1FAIpQLSfIh8z6IsyO1QPY_B7SLRQO670wsRGeO0_uUYMwJtATt5xz4g/viewform)

### Public Result Form Prompts

###### Wait Time Queries Prompts
+ [wait_time_granting_request_good](https://gist.github.com/ACC25/afc46f97a452066066de3d81d92b3b09)
+ [wait_time_denying_request_good](https://gist.github.com/ACC25/fb92ef1830633fc0e685dcf7f151e1d4)
+ [wait_time_denying_request_bad](https://gist.github.com/ACC25/9ff0d79cb34a32e9a07459759d12af5c)
###### Warranty Queries Prompts
+ [warranty_granting_request_good](https://gist.github.com/ACC25/40b81154cd968225beaf37bd61606097)
+ [warranty_denying_request_good](https://gist.github.com/ACC25/0200d775b4efc996e3200ba1e19b4464)
+ [warranty_denying_request_bad](https://gist.github.com/ACC25/ebf6aa3bb0905f0cce3397f75fd4f46b)

### Possible interactions

#### Surfboards

+ Querying inventory on already built boards
+ Querying wait times for building a board
+ Querying warranty policy

#### Accessories

+ Querying inventory on accessories
+ Querying warranty policy
