# Gijsbertsen-hextool

Een open-source AI-gestuurde tool voor het bewerken van BMW ECU bin-files.

![Gijsbertsen-hextool Logo](docs/logo.png)

## Functionaliteiten

- 🔍 **Automatische ECU detectie**: Herkenning van BMW DME, DSC, DTC systemen
- 🧠 **AI-gestuurde suggesties**: Intelligente voorstellen voor aanpassingen
- 🔧 **VIN aanpassing**: Wijzig of lees chassisnummers (VIN)
- 🏭 **ECU Virginizen**: Reset ECU's naar fabrieksinstellingen
- ✅ **Checksum beheer**: Automatische correctie van checksums
- 🔄 **SMG naar DSC Conversie**: Speciale conversie voor E90 M3
- 📦 **Multi-format ondersteuning**: Compatibel met Autotuner, Microtronics, etc.

## Ondersteunde BMW Modellen (2004-2020)

- E60/E61 serie (2004-2010)
- E90/E91/E92/E93 serie (2005-2013)
- F10/F11 serie (2010-2017)
- F30/F31/F32/F33 serie (2012-2020)
- En meer...

## Installatie

### Vereisten

- Python 3.8 of hoger
- Git (voor het klonen van de repository)

### Snel starten

```bash
# Clone de repository
git clone https://github.com/jouw-username/gijsbertsen-hextool.git
cd gijsbertsen-hextool

# Installeer benodigde packages
pip install -r requirements.txt

# Voer uit met een voorbeeld bin-file
python gijsbertsen.py -f voorbeelden/example.bin --info
