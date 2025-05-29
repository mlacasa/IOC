# 📚 Fitxes Interactives IOC - Matemàtiques

[![Python](https://img.shields.io/badge/Python-3.7%2B-blue)](https://python.org)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange)](https://jupyter.org)
[![Google Colab](https://img.shields.io/badge/Google-Colab-yellow)](https://colab.research.google.com)
[![Llicència](https://img.shields.io/badge/Llicència-MIT-green)](LICENSE)

## 🎯 Descripció

Col·lecció de fitxes interactives per a l'aprenentatge de matemàtiques dirigides als estudiants de l'**Institut Obert de Catalunya (IOC)**. Aquestes fitxes combinen teoria, exemples pràctics i codi executable per facilitar la comprensió de conceptes matemàtics complexos.

## 📋 Contingut del Repositori

### 🔢 Sistemes d'Equacions Lineals
- **Teoria completa**: Explicació pas a pas del mètode de Gauss-Jordan
- **Codi interactiu**: Resolució automàtica de sistemes 3x3
- **Exemples pràctics**: Casos reals amb solucions detallades
- **Verificació**: Comprovació automàtica de resultats

### ✨ Característiques
- 📱 **Interfície intuïtiva** amb menús i guies pas a pas
- ⏱️ **Visualització temporal** amb pauses educatives
- 🔍 **Anàlisi automàtica** del tipus de sistema
- ✅ **Verificació de resultats** amb fraccions exactes
- 🎓 **Orientació pedagògica** amb explicacions detallades

## 🚀 Com Utilitzar les Fitxes

### Opció 1: Google Colab (Recomanada)
1. Clica el botó **"Open in Colab"** de cada fitxa
2. Executa les cel·les seqüencialment
3. Segueix les instruccions interactives

### Opció 2: Jupyter Notebook Local
1. Descarrega els fitxers `.ipynb`
2. Obre'ls amb Jupyter Notebook
3. Executa les cel·les

### Opció 3: Només Codi Python
1. Copia el codi Python de les cel·les
2. Executa'l en qualsevol entorn Python

## 📁 Estructura del Repositori

```
📦 fitxes-interactives-ioc/
├── 📂 sistemes-equacions/
│   ├── 📓 teoria-sistemes-3x3.ipynb
│   ├── 📓 codi-interactiu-gauss.ipynb
│   ├── 📄 exemples-resolts.md
│   └── 🐍 sistema_gauss.py
├── 📂 recursos/
│   ├── 🖼️ imatges/
│   └── 📊 exemples-dades/
├── 📄 README.md
└── 📄 LICENSE
```

## 🛠️ Requisits

### Per Google Colab
- ✅ Compte Google (gratuït)
- ✅ Navegador web actualitzat
- ✅ Connexió a internet

### Per instal·lació local
```bash
# Python 3.7 o superior
python --version

# Paquets necessaris
pip install numpy
pip install fractions
pip install jupyter
```

## 🎓 Per a Estudiants

### Com començar
1. **Llegeix la teoria** abans d'executar el codi
2. **Experimenta** amb diferents exemples
3. **Comprova** els resultats manualment
4. **Pregunta** si tens dubtes als fòrums de l'IOC

### Consells d'aprenentatge
- 📖 **Segueix l'ordre** de les fitxes
- ✍️ **Pren notes** mentre executes
- 🔄 **Repeteix** els exercicis fins dominar-los
- 👥 **Comparteix** amb companys per aprendre junts

## 👨‍🏫 Per a Professors

### Integració a l'aula
- **Demostracions en directe**: Executa el codi durant les classes
- **Tasques individuals**: Assigna exercicis específics
- **Projectes grupals**: Usa les fitxes com a base per projectes
- **Avaluació**: Crea exercicis similars per examens

### Personalització
- **Modifica els exemples** per adaptar-los al currículum
- **Afegeix nous exercicis** seguint la mateixa estructura
- **Integra amb altres topics** del curs

## 🔧 Instal·lació i Configuració

### Clonar el repositori
```bash
git clone https://github.com/[usuari]/fitxes-interactives-ioc.git
cd fitxes-interactives-ioc
```

### Configurar l'entorn virtual
```bash
python -m venv venv
source venv/bin/activate  # Linux/Mac
# o
venv\Scripts\activate     # Windows

pip install -r requirements.txt
```

### Executar Jupyter
```bash
jupyter notebook
```

## 📖 Exemples d'Ús

### Sistema compatible determinat
```python
# Sistema: x + 2y + 5z = 7
#         3x - 2y + 5z = -9  
#         2x + 0y + 4z = 5
# Solució: x = 13, y = 12, z = -6
```

### Sistema compatible indeterminat
```python
# Sistema amb infinites solucions
# Expressió paramètrica de la solució
```

### Sistema incompatible
```python
# Sistema sense solució
# Explicació del perquè no té solució
```

## 🤝 Contribucions

Les contribucions són benvingudes! Si vols col·laborar:

1. **Fork** el repositori
2. **Crea** una branca per la teva funcionalitat
3. **Commiteja** els canvis
4. **Fes** un Pull Request

### Tipus de contribucions
- 🐛 **Correccions de bugs**
- ✨ **Noves funcionalitats**
- 📚 **Millores en documentació**
- 🎨 **Millores en disseny**
- 🌍 **Traduccions**

## 📄 Llicència

Aquest projecte està llicenciat sota la **Llicència MIT** - veure [LICENSE](LICENSE) per més detalls.

### Resum de la llicència
- ✅ Ús comercial i personal
- ✅ Modificació i distribució
- ✅ Ús privat
- ❌ Responsabilitat dels autors

## 🙏 Agraïments

- **Institut Obert de Catalunya (IOC)** per la seva dedicació a l'educació digital
- **Comunitat educativa** per les seves aportacions i feedback
- **Desenvolupadors open source** per les seves eines i llibreries

## 📞 Contacte i Suport

### Per estudiants IOC
- 💬 **Fòrums de l'IOC**: Consulta amb professors i companys
- 📧 **Correu IOC**: Contacta amb el teu tutor
- 📱 **Grup d'estudi**: Uneix-te al grup de matemàtiques

### Per a desenvolupadors
- 🐛 **Issues**: [GitHub Issues](https://github.com/[usuari]/fitxes-interactives-ioc/issues)
- 💡 **Discussions**: [GitHub Discussions](https://github.com/[usuari]/fitxes-interactives-ioc/discussions)
- 📧 **Email**: [email@exemple.com]

## 🔗 Enllaços Útils

- 🏫 [Institut Obert de Catalunya](https://ioc.xtec.cat/)
- 📚 [Documentació Python](https://docs.python.org/3/)
- 🪐 [Google Colab](https://colab.research.google.com/)
- 📓 [Jupyter Project](https://jupyter.org/)
- 🔢 [NumPy Documentation](https://numpy.org/doc/)

## 📊 Estadístiques

![GitHub stars](https://img.shields.io/github/stars/[usuari]/fitxes-interactives-ioc)
![GitHub forks](https://img.shields.io/github/forks/[usuari]/fitxes-interactives-ioc)
![GitHub issues](https://img.shields.io/github/issues/[usuari]/fitxes-interactives-ioc)
![GitHub pull requests](https://img.shields.io/github/issues-pr/[usuari]/fitxes-interactives-ioc)

---

<div align="center">

**📚 Fet amb ❤️ per la comunitat educativa de l'IOC**

[⬆️ Torna a dalt](#-fitxes-interactives-ioc---matemàtiques)

</div>
