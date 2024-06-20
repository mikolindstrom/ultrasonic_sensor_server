synapses:
  - name: "measure-distance"
    signals:
      - order: "distance"
    neurons:
      - ultrasonic_sensor:
          trigger_pin: 23
          echo_pin: 24
