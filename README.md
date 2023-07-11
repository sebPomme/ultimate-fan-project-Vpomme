# Ultimate Fan Project Version pomme
Converting any 3-Speed fan for Home Assistant control with ESPHome and a relay board.
Based on [3ative ultimate-fan-project-V3](https://github.com/3ative/ultimate-fan-project-V3/tree/main)

#### Differences with [3ative ultimate-fan-project-V3](https://github.com/3ative/ultimate-fan-project-V3/tree/main)
- Use of [esphome speed fan](https://esphome.io/components/fan/speed.html) object. In order to expose directly a FAN in home assistant point of view.
- Use Athom 4 relay board (3 needed for this project)

#### Note
- I didn't found an home assistant card to directly expose the fan quick access. This is why I keep the esphome "number"
- ESPHome Code: [ultimate-fan-project-Vpomme.yaml](ultimate-fan-project-Vpomme.yaml)
- Custom Button: [Button_Card_Fan.yaml](Button_Card_Fan.yaml) (need [button-card](https://github.com/custom-cards/button-card) to work)

The result:  
![How it's works](exemple.gif)  

#### Dont forget to check
- [The ultimate and original project](https://github.com/3ative/ultimate-fan-project-V3/tree/main)
- [The 3ative youtube video about his own project](https://youtu.be/_XgJyYwlejo)
