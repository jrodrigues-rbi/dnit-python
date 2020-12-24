# DNIT.md

<h1>Pré-requisitos</h1>
<ul>
    <li>CentOS 7</li>
        <ul>
            <li>wget https://dl.google.com/linux/direct/google-chrome-stable_current_x86_64.rpm</li>
            <li>yum localinstall google-chrome-stable_current_x86_64.rpm</li>
            <li>wget https://chromedriver.storage.googleapis.com/2.41/chromedriver_linux64.zip</li>
            <li>unzip chromedriver_linux64.zip</li>
            <li>sudo mv chromedriver /usr/bin/chromedriver</li>
            <li>sudo chown root:root /usr/bin/chromedriver</li>
            <li>sudo chmod +x /usr/bin/chromedriver</li>
        </ul>
    <li>Python >=3.6</li>
        <ul>
            <li>yum install python (certifique-se que está na versão 3.6 ou superior)</li>
            <li>pip3 install selenium</li>
        </ul>
</ul>

  