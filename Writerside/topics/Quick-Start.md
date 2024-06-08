# Quick Start

To use Intellij-Move plugin you'll need any of the Jetbrains IDE installed on your system. 

There's a number of free options:
* [RustRover IDE](https://www.jetbrains.com/rust/)
* [Intellij IDEA Community Edition](https://www.jetbrains.com/idea/download/#:~:text=IntelliJ%20IDEA%20Community%20Edition)
* [Pycharm Community](https://www.jetbrains.com/pycharm/download/#:~:text=PyCharm%20Community%20Edition)
* [Android Studio](https://developer.android.com/studio)

You can also use Jetbrains paid products, like CLion, Intellij Ultimate, etc. 

## RustRover IDE

RustRover has a free non-commercial license available. To download it, 
go to the https://www.jetbrains.com/rust/download/.   

## Intellij IDEA Community Edition

Intellij IDEA CE is a free IDE from Jetbrains, which has Java/Kotlin support built-in, 
but also allows installing all the free plugins from the ecosystem. 

To install the Intellij IDEA product, use the [official Intellij IDEA installation guide](https://www.jetbrains.com/help/idea/installation-guide.html).

## PyCharm Community Edition

PyCharm CE is free Python IDE from Jetbrains. It also allows installing all free plugins from the JetBrains Marketplace.

To install the base PyCharm Community Edition, 
use the [official installation guide](https://www.jetbrains.com/help/pycharm/installation-guide.html).

## Install EAP version of the plugin

Besides stable releases of the plugin, we also release the EAP version, which builds every time there's 
a code merged into the master branch.

To use those EAPs, you need to enable EAP repos in your plugins settings: 

1. Open **Settings | Plugins**, click on gear icon on the right. 

2. Select **Manage Plugin Repositories...** from the dropdown. 

3. Click "+", enter `https://plugins.jetbrains.com/plugins/eap/list` and click OK. 

4. Restart your IDE, go to the **Settings | Plugins** once again and update your Move Language plugin. 

![Add EAP plugin repository](eap-channel.gif)


