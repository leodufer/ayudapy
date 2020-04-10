# ayudaPy
Platform to help people help people
#### URL

https://ayudapy.org

## Requirements

* Python 3.6+
* Django 2.2+
* PostGIS 3.0+

## Install
GeoDjango https://kitcharoenp.github.io/gis/2018/06/12/geodjango_installation.html

```
git clone git@github.com:melizeche/ayudapy.git
cd ayudapy
python3 -m venv env
source env/bin/activate
pip install -r requirements.txt
cp conf/settings.py.example conf/settings.py # you should edit this file with your configuration
./manage.py migrate
./manage.py runserver
```

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## Author

* Marcelo Elizeche Landó https://github.com/melizeche

## Contributors / Thanks

* Agustin Gómez https://github.com/gomezag
* Carlos Vallejos  https://github.com/cabupy
* Diosnel Velázquez https://github.com/diosnelv
* Juan Hüttemann https://github.com/juanhuttemann

## TODO

* Documentation
* Support geolocation
* Captcha
* ~~Create models~~
* Users(?)

More in [TODO.md](TODO.md)

## License

This project is licensed under the terms of the GNU General Public License v3.0 - see the [LICENSE](LICENSE) file for details

