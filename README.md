# Previsor de Choro

**Previsor de Choro** é uma aplicação que utiliza **redes neurais convolucionais (CNN)** para prever a razão do choro de um bebé com base numa gravação de áudio em formato mp3. O objetivo é fornecer uma análise rápida e precisa do motivo pelo qual o bebé está a chorar, ajudando pais e cuidadores a responder de forma adequada e rápida às necessidades da criança.

### Funcionamento

1. **Transformada Rápida de Fourier (FFT)**:
   - Após a gravação do choro, a aplicação processa o áudio utilizando uma **Transformada Rápida de Fourier (FFT)** para gerar um espectrograma, que será utilizado para extrair características importantes. 
   ![FFT](FFT.JPG)

2. **Rede Neural Convolucional (CNN)**:
   - O espectrograma gerado é analisado através de uma **Rede Neural Convolucional (CNN)** pré-treinada, que identifica padrões no áudio que indicam a razão do choro, como fome, cansaço, desconforto, entre outros.
   ![CNN](CNN.JPG)

### Características

- **Previsão automática** das razões do choro (fome, cansaço, dor, etc.)
- **Respostas personalizadas** com base no motivo identificado (por exemplo, tocar uma canção de embalar se o bebé estiver cansado).
- **Integração com Firebase** para sincronização de dados entre o dispositivo Android e o servidor.

### Tecnologias Utilizadas

- **Python** (para o processamento de áudio e machine learning)
- **Keras e TensorFlow** (para a implementação da rede neural)
- **Android** (para a interface do utilizador e interação com o dispositivo)
- **Firebase** (para armazenamento e sincronização de dados)

