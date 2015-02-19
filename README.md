![Open Data Day 2015 - Brasilia](https://github.com/calangohc/open-data-day-2015/logo_opendataday_brasilia_2015.png)

# Open Data Day 2015 - Brasilia

## Oficina de Navegação pela API da Camara dos Deputados

Para instalar os softwares desta oficina, você precisa ter concluido com exito os passos da instalação do [Kit do Mochileiro de Dados](https://github.com/calangohc/open-data-day-2015).

### Instruções
1. Abra um terminal:
2. Clone o repositório para a oficina:
```bash
git clone https://github.com/calangohc/cd-odd2015
cd cd-odd2015
```
3. Acione o virtualenvwrapper e crie um virtualenv para esta oficina:
```bash
source $(which virtualenvwrapper.sh)
mkvirtualenv cd-odd2015
```
4. Instale os pacotes e bibliotecas necessárias:
```bash
pip install -r requirements.txt
```
5. Execute o app
```bash
python app/app.py
```