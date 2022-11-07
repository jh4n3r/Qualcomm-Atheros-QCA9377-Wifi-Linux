# Qualcomm-Atheros-QCA9377-Wifi-Linux
Controladores y firmware para Qualcomm Atheros QCA9377 Driver 0042 [rev. 30]. Este repositorio también contiene PKGBUILD para Arch Distribution y un script bash genérico para cualquier distribución GNU\Linux.

Este reparto está fuerna de mantenimiento. 

##Para la distribución Arch Linux makepkg -i

##Para cualquier distribución chmod +x install.sh

./instalar.sh

###Para Kernel 4.4-rc2 Compile su propio kernel aplicando qca9377_hw1.1_for_linux_4.4-rc2.patch al código fuente del kernel.

Use los pasos de compilación del kernel específicos de la distribución (lea más sobre esto en las páginas wiki de su distribución).

chmod +x install_for_kernel_4.4-rc2.sh

./instalar_para_kernel_4.4-rc2.sh
