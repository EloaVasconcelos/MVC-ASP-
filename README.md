# MVC-ASP-

ABRIAR UMA NOVO RESULTADO EM CIMA DA PASTA CLIENTE 

<h2>Resultado</h2>

<div>

    <hr />
    <dl class="dl-horizontal">

        <dt>
            @Html.DisplayNameFor(model => model.Nome)
        </dt>

        <dd>
            @Html.DisplayFor(model => model.Nome)
        </dd>


        <dt>
            @Html.DisplayNameFor(model => model.Endereco)

        </dt>

        <dd>
            @Html.DisplayFor(model => model.Endereco)
        </dd>

        <dt>
            @Html.DisplayNameFor(model => model.Telefone)
        </dt>

        <dd>
            @Html.DisplayFor(model => model.Telefone)
        </dd>

        <dt>
            @Html.DisplayNameFor(model => model.Email)
        </dt>

        <dd>
            @Html.DisplayFor(model => model.Email)
        </dd>

        <dt>
            @Html.DisplayNameFor(model => model.CPF)
        </dt>

        <dd>
            @Html.DisplayFor(model => model.CPF)
        </dd>

        <dt>
            @Html.DisplayNameFor(model => model.DataNascimento)
        </dt>

        <dd>
            @Html.DisplayFor(model => model.DataNascimento)
        </dd>



    </dl>
</div>
<p>
    @Html.ActionLink("Voltar", "Index")
</p>

