
🔐 Secrets no Kubernetes carecem de criptografia 🚨

Durante minhas pesquisas ao analisar como o secrets do Kubernetes são armazenados, percebi que eles são apenas codificados em Base64, sem criptografia real, o que significa que dados sensíveis como credenciais e chaves, podem ser expostos facilmente se não houver um cuidado extra. 
🚨☠️🚨

💡🕵️‍♂️ Para este problema busquei a seguinte resolução: 👨‍💻

Para redução de riscos eu criei um armazenamento seguro para chaves SSH RSA de 4096 bits, garantindo que o diretório /root/.ssh tivesse permissões restritas. E que mesmo usando recursos nativos do Kubernetes, é possível minimizar vulnerabilidades com configurações estratégicas.

🔹 Lições aprendidas:

 ✅ Redução de riscos é essencial em ambientes críticos 🧠
 ✅ Cultura de segurança deve ser parte da rotina de todos! 🛡️
 ✅ Atenção aos detalhes faz toda a diferença 🥰
 ✅ Seguir boas práticas no uso de secrets no Kubernetes é o mínimo que deve fazer. 💪🔥

💡 Conclusão: Manter secrets seguro no Kubernetes requer ação proativa e de muita atenção. Não basta confiar apenas no "padrão" — é necessário adotar boas práticas adicionais para evitar a exposição desnecessária de dados sensíveis. Ao utilizar os recursos nativos do Kubernetes de forma estratégica, é possível proteger credenciais sem comprometer a agilidade dos processos. 🚀🔒

Link: https://www.linkedin.com/posts/michele-bueno-283893a6_kubernetes-devsecops-seguranaexadainformaaexaeto-activity-7303845737631502336-L0F7/?utm_source=social_share_send&utm_medium=member_desktop_web&rcm=ACoAABaOLsMBjUNHWUX49pUlgw2wDVjDV0-3CQA
