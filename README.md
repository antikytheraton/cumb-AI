# Cumb-IA
- Electro Cuuuuumbiaaaa!!!!

![](./Cumb_IA.jpeg)
<!-- ## tensorflow-music-generator

generates music (midi files) using a Tensorflow Restricted Boltzman Machine

Read more about it on  Medium: https://medium.com/@m_ko/deep-learning-with-tensorflow-part-3-music-and-text-generation-370cf37bb071

Hear a demo of the result here:
https://www.youtube.com/watch?v=5wZIQ9XHNns&feature=youtu.be
 -->

## Generador de ritmos de electrocumbia
<!-- Use TensorFlow to generate short sequences of music with a [Restricted Boltzmann Machine](http://deeplearning4j.org/restrictedboltzmannmachine.html). 
Original code comes from YouTube, see here: (https://youtu.be/ZE7qWXX05T0) -->

## Dependencies

### Crear un entorno virtual con python 2.7

```bash
$ virtualenv RBM_ENV --python=python2.7
$ source RBM_ENV/bin/activate
```

  * [Tensorflow](https://www.tensorflow.org/versions/r0.10/get_started/os_setup.html)
  * pandas
  * numpy
  * msgpack-python
  * glob2
  * tqdm 
  * python-midi
  
<!-- Use [pip](https://pypi.python.org/pypi/pip) to install any missing dependencies (pip install --upgrade ... )  -->

### Para instalar las dependencias ejecutar en el entorno

```bash
pip install -r requirements.txt
```
<!-- ### Dependencies on Windows with python3
```
    pip install pandas
    pip install msgpack-python
    pip install numpy
    pip install glob2
    pip install tqdm
    pip install py-midi
    pip install python-midi
``` -->

## Como ejecutarlo
Para entrenar y generar musica, simplemente ejecutar
```
python rbm_chords.py
```

La data para entrenar se encuentra dentrol directorio Electro_Cumbia.

<!-- The training data goes in the Electro_Cumbia folder. You have to use MIDI files. You can find some [here](http://www.midiworld.com/files/).
I have already added pop songs.
Training will take 5-10 minutes on a modern laptop. The output will be a collection of midi files.

## Credits

The credit for this code goes to [dshieble](https://github.com/dshieble) and [llSourcell](https://github.com/llSourcell/Music_Generator_Demo)

Have fun! -->

