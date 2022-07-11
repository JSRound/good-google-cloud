# Billing

Lo fundamental, no se puede hacer nada respecto al Billing si no tenemos una cuenta con permisos
* [Overview of Cloud Billing access control](https://cloud.google.com/billing/docs/how-to/billing-access)
    <details><summary>Details</summary>


    | Role  | Purpose  | Level |
    |---|---|---|
    | **Billing Account Creator (roles/billing.creator)**| Create new self-serve (online) billing accounts. | Organization

    Use this role for initial billing setup or to allow creation of additional billing accounts.
    Users must have this role to sign up for Google Cloud with a credit card using their corporate identity.
    Tip: Minimize the number of users who have this role to help prevent proliferation of untracked cloud spend in your organization.

    </details>


Una vez que tenemos una cuenta con permisos podemos crear un budget que nos mandara un email por defecto, pero no evita gastos
* [Crea, edita o borra presupuestos y alertas de presupuesto](https://cloud.google.com/billing/docs/how-to/budgets)
