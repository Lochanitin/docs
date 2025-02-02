---
title: Início rápido para educadores do GitHub
intro: 'Em cerca de 15 minutos, os professores podem começar com descontos, treinamentos e ferramentas para {% data variables.product.company_short %} e, em seguida, criar uma sala de aula para os alunos em um curso de desenvolvimento de software usando {% data variables.product.prodname_classroom %}.'
allowTitleToDifferFromFilename: true
versions:
  fpt: '*'
shortTitle: QuickStart
---

## Introdução

Os educadores que ministram um curso sobre desenvolvimento de software podem usar descontos, parcerias, treinamento e ferramentas a partir de {% data variables.product.prodname_education %} para ensinar efetivamente as habilidades relevantes aos alunos.

Neste guia, você começará com {% data variables.product.product_name %}, inscreva-se em contas e serviços com descontos por meio de {% data variables.product.prodname_education %} e crie um espaço para o seu curso e atividade em {% data variables.product.prodname_classroom %}.

{% tip %}

**Tip**: If you're a student and you'd like to take advantage of an academic discount, see "[Apply to {% data variables.product.prodname_global_campus %} as a student](/education/explore-the-benefits-of-teaching-and-learning-with-github-education/github-global-campus-for-students/apply-to-github-global-campus-as-a-student)."

{% endtip %}

## Criando contas em {% data variables.product.product_name %}

Primeiro, você precisará criar uma conta pessoal grátis em {% data variables.product.product_name %}.

{% data reusables.accounts.create-account %}
1. Siga as instruções para criar sua conta pessoal grátis.

Depois de criar a sua conta pessoal, crie uma conta grátis de organização. Você usará esta conta da organização para criar e gerenciar salas de aula de {% data variables.product.prodname_classroom %}.

{% data reusables.user-settings.access_settings %}
{% data reusables.user-settings.organizations %}
{% data reusables.organizations.new-organization %}
4. Siga as instruções para criar uma organização grátis.

Para obter mais informações, consulte "[Tipos de contas de {% data variables.product.prodname_dotcom %}](/github/getting-started-with-github/types-of-github-accounts)".

## Applying for teacher benefits

Next, you'll sign up for teacher benefits and resources from {% data variables.product.company_short %} by applying to {% data variables.product.prodname_global_campus %}, a portal that allows you to access your education benefits all in one place.  {% data reusables.education.educator-requirements %}

{% tip %}

**Dica** Além de descontos individuais, {% data variables.product.company_short %} oferece parcerias com instituições de ensino por meio de {% data variables.product.prodname_campus_program %}. Para obter mais informações, consulte o site [{% data variables.product.prodname_campus_program %}](https://education.github.com/schools).

{% endtip %}

{% data reusables.education.benefits-page %}
{% data reusables.education.click-get-teacher-benefits %}
{% data reusables.education.select-email-address %}
{% data reusables.education.upload-proof-status %}
{% data reusables.education.school-name %}
{% data reusables.education.plan-to-use-github %}
{% data reusables.education.submit-application %}

Once you are a verified {% data variables.product.prodname_global_campus %} educator, you can access {% data variables.product.prodname_global_campus %} anytime by going to the [{% data variables.product.prodname_education %} website](https://education.github.com).

## Configurar {% data variables.product.prodname_classroom %}

Com sua conta pessoal e conta de organização, você está pronto para dar os primeiros passos com {% data variables.product.prodname_classroom %}. {% data variables.product.prodname_classroom %} é grátis para usar. Você pode acompanhar e gerenciar as recomendações, avaliar o trabalho automaticamente e dar feedback aos seus alunos.

{% data reusables.classroom.sign-into-github-classroom %}
1. Para autorizar {% data variables.product.prodname_classroom %} para acessar a sua conta pessoal em {% data variables.product.prodname_dotcom %}, revise as informações e, em seguida, clique em **Autorizar {% data variables.product.prodname_classroom %}**. ![Botão "Autorizar {% data variables.product.prodname_classroom %}" para a conta pessoal](/assets/images/help/classroom/setup-click-authorize-github-classroom.png)
1. Revise as informações. Para autorizar {% data variables.product.prodname_classroom %} a acessar sua conta de organização em {% data variables.product.prodname_dotcom %}, clique em **Conceder**. ![Botão "Conceder" para organização](/assets/images/help/classroom/setup-click-grant.png)

  {% tip %}

  **Dica**: Se você vir um botão **Solicitar** em vez de um botão de **Conceder**, significa que você é integrante da organização, não um dono. Um proprietário deve aprovar sua solicitação para {% data variables.product.prodname_classroom %}. Você precisa ser o proprietário da organização para criar e gerenciar as salas de aula e as atividades em {% data variables.product.prodname_classroom %}. Para obter mais informações, consulte "[Autorizar aplicativos OAuth](/github/authenticating-to-github/authorizing-oauth-apps#oauth-apps-and-organizations)".

  {% endtip %}

1. Clique em **Autorizar github**. ![Clique no botão "Autorizar" para a organização](/assets/images/help/classroom/setup-click-authorize-github.png)

## Crie sua sala de aula

{% data reusables.classroom.about-classrooms %}

{% data reusables.classroom.sign-into-github-classroom %}
1. Clique em **Criar sua primeira sala de aula** ou **Nova sala de aula**.
{% data reusables.classroom.guide-create-new-classroom %}

## Próximas etapas

Você criou uma sala de aula e está pronto para enriquecer seu curso com {% data variables.product.product_name %} e {% data variables.product.prodname_classroom %}!  🎉

- Assista a alguns vídeos sobre {% data variables.product.prodname_classroom %}. Para obter mais informações, consulte "[Fundamentos da configuração de {% data variables.product.prodname_classroom %}](/education/manage-coursework-with-github-classroom/basics-of-setting-up-github-classroom)".
- Gerencie suas salas de aula e administradores da sala de aula e crie uma lista de estudantes para sua sala de aula. Para obter mais informações, consulte "[Gerenciar salas de aula](/education/manage-coursework-with-github-classroom/manage-classrooms)".
- Utilize o Git e a atividade inicial de {% data variables.product.company_short %} para dar aos alunos uma visão geral do Git e dos princípios básicos de {% data variables.product.product_name %}. Para obter mais informações, consulte "[Use a atividade inicial do Git e {% data variables.product.company_short %}](/education/manage-coursework-with-github-classroom/use-the-git-and-github-starter-assignment)".
- Crie uma atividade para alunos individualmente ou para equipes. {% data reusables.classroom.for-more-information-about-assignment-creation %}
- Escreva e implemente testes automatizados para dar feedback imediato aos alunos diretamente nos repositórios de atividade. Para obter mais informações, consulte "[Usar avaliação automática](/education/manage-coursework-with-github-classroom/use-autograding).
- Participar de {% data variables.product.prodname_education_community_with_url %}.
