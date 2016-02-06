# dportscanner
Python Port Scanner with Nmap

dportscanner - 2016.02.06

DPORTSCANNER IS A PYTHON LIBRARY  THAT SCANS PORTS OF IPs

Author :

* DAVID MWANGI -
    dmwangimail@gmail.com
    dexter@blackspacekenya.com
    www.blackspace.co.ke

Licence : GPL v3 or any later version

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program.  If not, see <http://www.gnu.org/licenses/>.

REQUIRED
 dtld library
  TO DOWNLOAD DTLD
      LINUX
        pip install dtld1.0
      WINDOWS
        python -m pip install dtld1.0
        py -3 -m pip install dtld1.0

Ideally,Dportscanner should download the latest dtld automatically.In the event of download
failure the above download instructions should work.

HOW TO USE

from dportscanner.scan import PortScanner
app = PortScanner('https://google.com')
ip = app.scan()  #returns a dict with keys : status,protocols,ports
print(ip['status'])
print(ip['protocols'])
PORT = ip['ports']
print(PORT[0])

HOW TO DOWNLOAD
UNIX
    pip install dportscanner

WINDOWS
    PYTHON 2
        py -m pip install dportscanner
    PYTHON 3
        py -3 -m pip install dportscanner






