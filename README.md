# 🏛️ Centro

## 🇺🇸 Overview & Intent
Published site host, study center portal, and manual repository for **centro.doutrina.org**. Its primary intent is to provide an independent, specialized reference portal for study centers, combining the standard Kardec codification shelf profiles with localized operational manuals and customized center tools.

### Architecture & Code Choices
* **Hosting Platform:** GitHub Pages configured with custom domain CNAME targeting `centro.doutrina.org`.
* **Selective Deployment Logic:** Specialized CI/CD rules implemented in `librus-shell` workflows that deploy core SPA updates while strictly preserving local host overrides (`flavor.json`, `manual/`, and `instance/` directories).
* **Modular Configuration:** Isolated configuration boundaries enabling individual study centers to maintain local documentation alongside global digital libraries.

### Site Map & Repository Structure
* `flavor.json` — Host-specific flavor profile and configuration parameters.
* `manual/` — Operational documentation and study center reference guides.
* `instance/` — Local site customizations, instance-specific assets, and metadata.
* Root / `assets/` — Compiled global SPA engine files managed by automated upstream deployments.

### Contributing & Volunteer Onboarding
Contributors interested in local study center tool integrations, manual documentation updates, or specialized layout configurations are welcome to submit pull requests directly to this repository.

---

## 🇧🇷 Visão Geral & Intenção
Host de site publicado, portal de centro de estudos e repositório de manuais para **centro.doutrina.org**. Sua intenção principal é fornecer um portal de referência independente e especializado para centros de estudo, combinando os perfis de prateleira padrão da codificação de Kardec com manuais operacionais localizados e ferramentas customizadas para os centros.

### Arquitetura & Escolhas de Código
* **Plataforma de Hospedagem:** GitHub Pages configurado com CNAME de domínio personalizado direcionado a `centro.doutrina.org`.
* **Lógica de Implantação Seletiva:** Regras especializadas de CI/CD implementadas nos fluxos de trabalho do `librus-shell` que implantam atualizações centrais da SPA enquanto preservam estritamente as substituições locais do host (diretórios `flavor.json`, `manual/` e `instance/`).
* **Configuração Modular:** Limites de configuração isolados que permitem que centros de estudo individuais mantenham documentação local juntamente com bibliotecas digitais globais.

### Mapa do Site & Estrutura do Repositório
* `flavor.json` — Perfil de sabor específico do host e parâmetros de configuração.
* `manual/` — Documentação operacional e guias de referência para centros de estudo.
* `instance/` — Customizações locais do site, ativos específicos da instância e metadados.
* Raiz / `assets/` — Arquivos do motor global da SPA compilados e gerenciados por implantações upstream automatizadas.

### Contribuição & Integração de Voluntários
Colaboradores interessados em integrações de ferramentas para centros de estudo locais, atualizações de manuais de documentação ou configurações de layout especializadas podem enviar pull requests diretamente para este repositório.
