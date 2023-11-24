# 1.5 Banco de dados de logs

![diagram](https://www.plantuml.com/plantuml/svg/0/XP9DRXGn48Nt8yqTYbvrIytq9YjMcJyWqW0HcO1OZIfsPMB9xR9SrGq1SHeM8mx02VfYoDr9aB9XPTb--jxpAv-BOjAkzVFP2nUCxop1dMgKLqsJyElYwFIkk-c4ak6W57HXk6tG9eUXzrticlNPoqkFGQ_VxHgFIgBD-komvZPooFeumkUptVBBX-lzuVF5_krXjtspVRyfgtn-TIzAxM7xJKkChePYUNbHrCLhJe4C0GhSTi4u3kYTHKi2be1lAIac44gz6quy7ch2896JKjv55C4ZkSG211GCjnGi2fIH4qGSPImG4ucYvJIH7uaLZ1HXxupBLYH2yi-mDDvHKAeM1OplM7DGT87IOSLTi9ZkozLciwkXM64md64MxPHqnqSfAlWndm40F7LLOcUTvWhooibXKHTxl26FKjG0nJAr-9q2Ff8Gy4bPFOSfcOoII4PPG8VV9ZWp1R0a57hslMifAF_7Xf_hH-VedS7XDFpY6ZvHak4FIGskZPwoQBhAPe7xQOh3AMloDDGiSk2VkRYFvAV9FzHrXRv785XrOXuY56F3vnJi-9d-0W00)

**Nível 5**:
Esse diagrama apresenta os elementos internos do Banco de dados de logs e a forma como comunicam-se entre si. O PostgreSQL atua como o repositório central para armazenar informações de logs de auditoria. Ele é responsável por garantir a integridade, consistência e segurança dos dados registrados pelas diferentes partes do sistema.

**Escopo**:Inclui diferentes partes do sistema que interagem com o banco de dados, como a aplicação principal, módulos específicos, ferramentas de administração, etc..

**Elementos Primários**: Banco de dados PostgreSQl, Aplicação principal, Módulos relacionados à auditoria, Ferramentas de administração.

**Público alvo**: Desenvolvedores do software.
