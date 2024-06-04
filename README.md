# RoomateDetector

```
RooMateDetector/
├── src/
│   ├── hardware/          # Código hardware
│   │   ├── pirSensor.ino
│   │   └── ... (otros archivos de hardware)
│   ├── server/            # servidor backend
│   │   ├── app.js
│   │   ├── routes/
│   │   │   ├── index.js
│   │   │   └── ... ( rutas)
│   │   ├── models/
│   │   │   ├── User.js
│   │   │   └── ... (otros modelos)
│   │   ├── controllers/
│   │   │   ├── notificationController.js
│   │   │   └── ... (otros controladores)
│   │   ├── config/
│   │   │   ├── database.js
│   │   │   └── ... (configuración)
│   │   └── utils/
│   │       ├── sendSMS.js
│   │       └── ... (otros utilitarios)
├── tests/
│   ├── hardware/
│   ├── server/
│   │   ├── routes/
│   │   ├── models/
│   │   ├── controllers/
│   │   └── utils/
│   └── ... (otros tests)
├── .gitignore
├── package.json
├── README.md
└── docs/
    ├── setup.md
    ├── usage.md
    └── api_reference.md
