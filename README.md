# Flask-React

Flask-React is a batteries included full stack Single Page App (SPA) meta-framework for Python and JavaScript based on the [Flask](http://flask.pocoo.org) and [React](http://reactjs.org) libraries.  

There are two components: 

* Flask Batteries Included (backend) - a list of packages that replicate all or almost all of the functionality of the popular Django framework when using Flask, plus some additional functionality
* React Batteries Included (frontend) - a list of packages that provides a cohesive framework experience when using React

## Flask Batteries Included

| Component                       | Library |
| ------------------------------- | ------- |
| Web framework                   | [Flask](http://flask.pocoo.org) |
| HTTP authentication             | [Flask-HTTPAuth](https://github.com/miguelgrinberg/Flask-HTTPAuth) |
| User session management         | [Flask-Login](https://github.com/maxcountryman/flask-login) |
| Email support                   | [Flask-Mail](https://github.com/mattupstate/flask-mail) |
| Forms                           | [Flask-WTF](https://github.com/wtforms/flask-wtf) |
| REST API generator              | [Flask-Restless](https://github.com/jfinkels/flask-restless) |
| Object relational mapper        | [SQLAlchemy](http://sqlalchemy.org) |
| &nbsp;&nbsp;&nbsp; Access control                  | [SQLAlchemy-Privileges](http://github.com/FlaskReact/sqlalchemy-privileges) |
| &nbsp;&nbsp;&nbsp; Data denormalization            | [SQLAlchemy-Utils](http://sqlalchemy-utils.readthedocs.io/en/latest/) |
| &nbsp;&nbsp;&nbsp; File and image storage          | [SQLAlchemy-ImageAttach](https://sqlalchemy-imageattach.readthedocs.io) |
| &nbsp;&nbsp;&nbsp; Full-text search                | [SQLAlchemy-Searchable](https://sqlalchemy-searchable.readthedocs.io/) (PostgreSQL),<br> [SQLAlchemy-FullTextSearch](https://github.com/mengzhuo/sqlalchemy-fulltext-search) (MySQL) |
| &nbsp;&nbsp;&nbsp; Spatial database extension      | [GeoAlchemy2](https://geoalchemy-2.readthedocs.io) |
| &nbsp;&nbsp;&nbsp; Migrations                      | [Alembic](http://alembic.zzzcomputing.com), [Flask-Migrate](https://flask-migrate.readthedocs.io/en/latest/) |
| Localization and display        | [Flask-BabelPlus](https://flask-babelplus.readthedocs.io/en/latest/), [Flask-Humanize](https://github.com/vitalk/flask-humanize) |
| Cache                           | [Flask-Caching](https://flask-caching.readthedocs.io/en/latest/) |
| Static pages                    | [Flask-FlatPages](https://flask-flatpages.readthedocs.io/en/latest/) |
| Admin                           | [Flask-Admin](https://flask-admin.readthedocs.io)
| Socket.io server                | [Flask-SocketIO](https://flask-socketio.readthedocs.io/en/latest/index.html) |
| Environment management          | [Python-Dotenv](https://github.com/theskumar/python-dotenv) |
| Task runner                     | [Celery](http://celeryproject.org), [Flower](https://flower.readthedocs.io) |
| Web server                      | [gunicorn](http://gunicorn.org) |

## React Batteries Included

| Component                       | Library |
| ------------------------------- | ------- |
| Views                           | [React](https://reactjs.org/) |
| Form validation                 | [Formik](https://formik.org) |
| Router                          | [React Router v3](https://github.com/ReactTraining/react-router/tree/v3), [react-router-named-routes](https://github.com/adamziel/react-router-named-routes) |
| Models                          | [Backbone](http://backbonejs.org), [Backbone-relational](http://backbonerelational.org), [backbone.trackit](https://github.com/nytimes/backbone.trackit), [backbone.iobind](https://github.com/noveogroup/backbone.iobind) |
| Data loading                    | [React JSON API](https://github.com/FlaskReact/react-jsonapi) |
| Document head manager           | [React Helmet](https://github.com/nfl/react-helmet) |
| CSS modules                     | [babel-plugin-react-css-modules](https://github.com/gajus/babel-plugin-react-css-modules) |
| Testing                         | [Mocha](https://mochajs.org/), [Chai](https://www.chaijs.com/), [Sinon](https://sinonjs.org/), [Enzyme](https://enzymejs.github.io/enzyme/) |
| ES6 transpiler                  | [Babel](https://babeljs.io/) |
| Module bundler                  | [Rollup](https://rollupjs.org) |
| Styled UI components            | [React Bootstrap](https://react-bootstrap.github.io/), [Material UI](https://material-ui.com/) |
| Server-side rendering           | [Node.js](https://nodejs.org/en/) |

