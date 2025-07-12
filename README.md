# adversarial_autoencoder
AAE for semi-supervised learning


🎯 ¿Se puede clasificar dígitos dibujados a mano con solo 200 imágenes etiquetadas?

Con [gonza] nos propusimos responder esa pregunta entrenando un modelo de aprendizaje profundo en un escenario semi-supervisado real.

🧠 Utilizamos un Autoencoder Adversarial (AAE), una arquitectura que combina autoencoders con entrenamiento tipo GAN, para separar la información de clase y estilo en el espacio latente.

🏷️ Solo usamos 200 imágenes etiquetadas del dataset MNIST, y el resto sin etiquetas.

📊 Resultado: 80 % de accuracy sobre el test set estándar y un modelo capaz de reconocer números escritos a mano.

🔧 Exploramos cómo los discriminadores adversariales regulan el espacio latente y qué tan difícil es alcanzar un equilibrio entre encoder y discriminadores. También experimentamos con regularización, normalización y distintas funciones de pérdida.

📚 Basado en el paper:

Adversarial Autoencoders — Makhzani et al. (2016)

🔗 https://arxiv.org/pdf/1511.05644v2
