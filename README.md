[
    {
        "id": "37e6300f8a383912",
        "type": "function",
        "z": "3696906502618f0a",
        "name": "pressure",
        "func": "msg.payload = (msg.payload[0].pressure - msg.payload[1].pressure_1);\nif(msg.payload != 0 && msg.payload >= 0){\n    return msg;\n}",
        "outputs": 1,
        "noerr": 0,
        "initialize": "",
        "finalize": "",
        "libs": [],
        "x": 560,
        "y": 220,
        "wires": [
            [
                "14161e2bbf6dee27"
            ]
        ]
    }
]
