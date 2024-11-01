connect_device("Android:///")  # local adb device using default params
# local device with serial number SJE5T17B17 and custom params
connect_device("Android:///SJE5T17B17?cap_method=javacap&touch_method=adb")
# remote device using custom params Android://adbhost:adbport/serialno
connect_device("Android://127.0.0.1:5037/10.254.60.1:5555")
connect_device("Android://127.0.0.1:5037/10.234.60.1:5555?name=serialnumber")  # add serialno to params
connect_device("Windows:///")  # connect to the desktop
connect_device("Windows:///123456")  # Connect to the window with handle 123456
connect_device("windows:///?title_re='.*explorer.*'")  # Connect to the window that name include "explorer"
connect_device("Windows:///123456?foreground=False")  # Connect to the window without setting it foreground
connect_device("iOS:///127.0.0.1:8100")  # iOS device
connect_device("iOS:///http://localhost:8100/?mjpeg_port=9100")  # iOS with mjpeg port
connect_device("iOS:///http://localhost:8100/?mjpeg_port=9100&&udid=00008020-001270842E88002E")  # iOS with mjpeg port and udid
connect_device("iOS:///http://localhost:8100/?mjpeg_port=9100&&uuid=00008020-001270842E88002E")  # udid/uuid/serialno are all ok