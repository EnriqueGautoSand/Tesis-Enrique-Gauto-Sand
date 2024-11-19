# Tesis-Enrique-Gauto-Sand
 Repositorio de Tesis de Grado
En este Repositorio se van a subir los codigos utilizados durante el desarrollo de la Tesis.


A través del siguiente código se configuró la semilla en Keras para poder hacer pruebas replicables:

seed_value = 42
import random 
np.random.seed(seed_value)
random.seed(seed_value)
tf.random.set_seed(seed_value)
