# STM32-Hotspot/STM32WL_SubGHz_Phy_Basic_Tx_Rx MCU Firmware Package, based on STM32CubeWL Release v1.1.0

![latest tag](https://img.shields.io/github/v/tag/STMicroelectronics/STM32CubeWL.svg?color=brightgreen)

## Example

This Hotspot FW package includes:
* Application example under "Projects\NUCLEO-WL55JC\Applications\SubGHz_Phy" called SubGHz_Phy_Basic.     
   * This example implements a basic LoRa radio transmitter and receiver application between two STM32WL55xx devices (note, two NUCLEO-WL55JC1 are needed; for the Tx and Rx, respectively). The Tx device transmits a short 10 byte packet every 2s, and the Rx device receives these packets and displays the payload on the hyperterminal. 
   * The example also aims to demonstrate to the user how to configure the system (pinout, clocks, peripherals, utilities) and SubGhz middleware from STM32CubeMX to enable the radio in LoRa modulation mode, and show how to schedule and enable a transmission and receive operation from the firmware application.       
   * Development tools, toolchains/compilers: STM32CubeMX v6.4.0, IAR EWARM V9.10.2
   * Supported Devices and hardware boards: NUCLEO-WL55JC1
   * Known limitations: None

## Boards Needed

  * Two NUCLEO-WL55JC1
    * [NUCLEO-WL55JC](https://www.st.com/en/evaluation-tools/nucleo-wl55jc.html)

## Troubleshooting

**Caution** : Issues and the pull-requests are **not supported** to submit problems or suggestions related to the software delivered in this repository. The STM32WL_SubGHz_Phy_Basic_Tx_Rx example is being delivered as-is, and not necessarily supported by ST.

**For any other question** related to the product, the hardware performance or characteristics, the tools, the environment, you can submit it to the **ST Community** on the STM32 MCUs related [page](https://community.st.com/s/topic/0TO0X000000BSqSWAW/stm32-mcus).

Check also [STM32 Hotspot](https://github.com/stm32-hotspot)  from STMicroelectronics
