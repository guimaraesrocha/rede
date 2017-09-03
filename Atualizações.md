<!DOCTYPE html>
   <h1>Atualizações</h1>   
    <ul>
        <li>Versão 1.9 - 02SET2017</li>
            <h3><p>Novas Implementações</p></h3>
                <ul>
                    <li> Adicionado os campos "Porto de Procedência" e "Porto de Destino" na base de dados de Navios Fundeados.</li>
                    <li> Adicionado o campo "Total de Solicitações" na base de dados de Navios Fundeados, para verificar a frequência das solicitações de fundeio da Embarcação.</li>
                    <li> Adicionado nova base de dados que controla as perícias feitas pelo GVI no SISGEVI. Esta base de dados faz o controle conforme as datas das perícias cadastradas no sistema. O controle ocorre através de alertas visual e durante o cadastro de anuências e fundeios.</li>
                </ul>
            <h3><p>Correção Específica</p></h3>
                <ul>
                    <li> Corrigido o ERRO na função de verificar o tempo de 48h automaticamente no formulário, durante a inclusão de Navios Fundeados.</li>
                </ul>
            <h3><p>Melhoria de Performance</p></h3>
                <ul>
                    <li> Durante o cadastro de fundeios de Embarcações, o sistema verifica se há registros na base de dados de PEDRA e SISGEVI.</li>
                    <li> Durante o cadastro de Embarcações Esporte/Recreio, o sistema verifica se há registros na base de dados de PEDRA e SISGEVI.</li>
                    <li> Mudança na visualizacão das bordas de todos os campos do sistema, destacando-se a base de dados de Embarcações Esporte/Recreio.</li>
                </ul>
    </ul>
    <ul>
        <li>Versão 1.8 - 17JUL2017</li>
            <h3><p>Bug</p></h3>
                <ul>
                    <li> Corrigido o ERRO na função de verificar o tempo de 48h automaticamente no formulário, durante a inclusão de Navios Fundeados.</li>
                </ul>
            <h3><p>Novas Implementações</p></h3>
                <ul>
                    <li> Adicionado novo Layout em todos os formulários.</li>
                    <li> Suporte a PHP 7. Necessário reinstalar o sistema.</li>
                </ul>
            <h3><p>Correção Específica</p></h3>
                <ul>
                    <li> Devido a lentidão no sistema, a opção de gerar gráficos dinamicamente, foi retirada em todos os formulários.</li>
                    <li> Retirada a função de verificar o tempo de 48h automaticamente no formulário, durante a inclusão de Navios Fundeados.</li>
                </ul>
            <h3><p>Instalação</p></h3>
    	    	<ul>
    	        	<li> Lançamento oficial do sistema para as OMSUBO da CPRJ, DPC e PRIDIS.</li>
    	    	</ul>
    </ul>
    <ul>
        <li>Versão 1.7 - 10JUL2017</li>
             <h3><p>Melhoria de Performance</p></h3>
                <ul>
                    <li> Finalizado as correções específicas para adequar o sistema conforme a DCTIMBOTEC-31-002-2017 (Requisitos de SID para Homologacão de Sistemas Digitais).</li>
                </ul>
    </ul>
    <ul>
        <li>Versão 1.6 - 30JUN2017</li>
    	    <h3><p>Novas Implementações</p></h3>
    	            <ul>
    	                <li> Adicionada a função de forçar a mudanca de senha no formulário de cadastro de novos usuários.</li>
    	                <li> Alterado o campo Login do formulário do Usuário para conter tipo de dados somente números.</li>
    	                <li> Adicionado a opção de poder gerar gráficos dinamicamente em todos os formulários.</li>
    	            </ul>
        	<h3><p>Correção Específica</p></h3>
                <ul>
                    <li> Corrigido erro de inclusão do nome da OM no Menu.</li>
                    <li> Corrigido erro de inclusão do nome da OM no formulário OM.</li>
                </ul>
            <h3><p>Melhoria de Performance</p></h3>
                <ul>
                	<li> Alterada as mensagens de ERRO de todos os formulários.</li>
                </ul>
    </ul>
    <ul>
        <li>Versão 1.5 - 10JUN2017</li>
        	<h3><p>Correção Específica</p></h3>
                <ul>
                    <li> Iniciado correções específicas para adequar o sistema a DCTIMBOTEC-31-002-2017 (Requisitos de SID para Homologacão de Sistemas Digitais).</li>
                </ul>
            <h3><p>Melhoria de Performance</p></h3>
                <ul>
                	<li> Alterada a senha padrão do Administrador.</li>
                	<li> Criada novas "VIEWS" na Base de Dados. Necessário reinstalar o sistema.</li>
                </ul>
    </ul>
    <ul>
        <li>Versão 1.4 - 08MAI2017</li>
            <h3><p>Correção Específica</p></h3>
                <ul>
                    <li> Alterado o formulário Esporte e/ou Recreio, para adequar-se a NORMAM-03.</li>
                    <li> Corrigido problema no campo "DUV" no formulário Passe de Saída, que passa a aceitar somente números, antes aceitava caracter especial.</li>
                </ul>
    </ul>
    <ul>
        <li>Versão 1.3 - 07ABR2017</li>
            <h3><p>Novas Implementações</p></h3>
                <ul>
                    <li> Adicionado novas cores no formulário de Navios na Pedra.</li>
                    <li> Alterado posicionamento dos campos no formulário de Navios na Pedra.</li>
                    <li> Possibilidade do Supervisor cadastrar "Áreas de Fundeio", antes somente o Administrador.</li>
                </ul>
            <h3><p>Melhoria de Performance</p></h3>
                <ul>
                    <li>Melhoria na visualização do campo "Anuência" no formulário de Navios na Pedra.</li>
                </ul>
        </ul>
    <ul>
        <li>Versão 1.2 - 30MAR2017</li>
            <h3><p>Bug</p></h3>
                <ul>
                    <li> Corrigido problema de erro durante o cadastro de senha do usuário.</li>
                    <li> Corrigido problema de altenticação do usuário.</li>
                </ul>
            <h3><p>Novas Implementações</p></h3>
                <ul>
                    <li> Criado o formulário "Áreas de Fundeio".</li>
                </ul>
            <h3><p>Correção Específica</p></h3>
                <ul>
                    <li> No cadastro da senha no formulário, foi permitido adicionar todos os caracteres.</li>
                </ul>
    </ul>
    <ul>
        <li>Versão 1.1 - 05MAR2017</li>
        	<h3><p>Bug</p></h3>
                <ul>
                    <li> Corrigido problema durante o cadastro de novos usuários.</li>
                </ul>
        	<h3><p>Novas Implementações</p></h3>
                <ul>
                    <li> Criado nova interface da página de login.</li>
                    <li> Adicionada a função de verificar o tempo de 48h automaticamente no formulário, durante a inclusão de Navios Fundeados.</li>
                    <li> Adicionada a função de verificar se existe "Passe de Saída" para a DUV cadastrada, caso sim, o sistema envia uma mensagen informando a duplicidade.</li>
                    <li> Adicionada a função de automatizar a numeração do "Passe de Saída" no formulário, durante a inclusão do Passe de Saída.</li>
                    <li> Iniciado procedimentos de adequações junto as NORMAM-08 e 03.</li>
                </ul>
            <h3><p>Correção Específica</p></h3>
                <ul>
                	<li> Corrigido problema de padronização de tamanho dos campos em todos os formulários.</li>
                    <li> Corrigido correções de ortografia no Menu.</li>
                    <li> Corrigido problema no campo "DUV" que passa a aceitar caracter especial.</li>
                    <li> Desabilitado o "Bruteforce".</li>
                </ul>
            <h3><p>Melhoria de Performance</p></h3>
                <ul>
                    <li> Adicionado o "Nome de Usuário" em todos os formulários, antes era o NIP.</li>
                    <li> Alterado o método de exportação para PDF e XLS, para todos os formuários.</li>
                    <li> Adicionado cores no campo "Anuência" do formulário de Navios na Pedra.</li>
                    <li> Alterado o "Intervalo de Refresh" para 60seg no formulário de Navios na Pedra.</li>
                </ul>
    </ul>
    <ul>
        <li>Versão 1.0 - 19DEZ2016</li>
            <h3><p>Instalação</p></h3>
    	    	<ul>
    	        	<li> Lançamento oficial do sistema na CPRJ.</li>
    	    	</ul>
    </ul>
</body>
</html>
