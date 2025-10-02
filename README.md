# efi-lenovo-gaming-3i

EFI para hackintosh no laptop Lenovo Gaming 3i

Testado no macOS Monterey, BigSur e Ventura (Sonoma não testado, mas já há uma kext para wifi em versão alpha).

**IMPORTANTE:** A EFI para **`macOS Sequoia não possui wifi/bluetooth ativo`**, uma vez que a kext para o Intel Wifi não possui versão, nem mesmo beta, para Sequoia (o desenvolvimento ficou parado em uma kext beta para o Sonoma), sendo necessário utilizar conexão cabeada, dongle USB ou trocar a placa wifi/bluetooth interna para ter conexão com a internet.

### Hardware:

|Tipo|Modelo|Obs.|
|-|-|-|
|CPU|Intel Core i5 10300H||
|GPU|Nvidia GTX 1650 4GB|Não habilitada|
|Memória|2x16GB DDR4||
|Touchpad|Touchpad Synaptics||
|Ethernet|Realtek RTL 8111||
|Wifi/BT|Intel 9565|Kext específica por versão do macOS|
|Armaz.|SSD Kingston NV2 1TB|Linux instalado|
|Armaz.|SSD Original Lenovo NVME 256GB|macOS instalado|
|Armaz.|SSD SATA Goldenfir 1TB|Windows 11 instalado|
