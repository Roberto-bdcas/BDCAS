# Blue Dolphin Aquarium System - BDCAS

The aim of the project is provide a modular system that is able to control a tank (mainly marine but not only) .

The system is composed by different units based on ESP32:
- level control, finalized to control water level, osmosis water refill, osmosis filter. It use various level sensor and provide 3 pwer outputs.
  
- Temperature control, finalized to control temperature in the tank, warmer & chiller. It use two temperature probes and provide 3 pwer outputs.

- pH probe control, finalzed to control & measure pH in the tank, pH in Ca rector and ORP potential. it use for each probe an external adapter and classic glass probes.

- others units will be done in future.
  
  Each unit is equipped with small Oled display for main informations, interface is based on web interface, any device with a browser connected to wifi can be used.
  
  Finally a central unit (optional) based on Linux machine can be used to collect all information, have data storage for graph, remote access from pubblic DNS and much others functions.

  Detailed information on main web site : 


For more information, please refer to:

XXXXX

## Licensing

* HDL simulations released under `CERN-OHL-W-2.0` (https://cern-ohl.web.cern.ch/home)
* All software released under `LGPL-2.1-or-later` (https://www.gnu.org/licenses/old-licenses/lgpl-2.0.html)


## Disclaimer

This software & documents are provided by the copyright holders and contributors "as is" and any express or implied warranties, including, but not limited to, the implied warranties of merchantability and fitness for a particular purpose are disclaimed. in no event shall the copyright owner or contributors be liable for any direct, indirect, incidental, special, exemplary, or consequential damages (including, but not limited to, procurement of substitute goods or services; loss of use, data, or profits; or business interruption) however caused and on any theory of liability, whether in contract, strict liability, or tort (including negligence or otherwise) arising in any way out of the use of this software, even if advised of the possibility of such damage.
