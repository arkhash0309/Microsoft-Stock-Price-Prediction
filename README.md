<h1>Microsoft-Stock-Price-Prediction</h1>
<h2>Making predictions on Microsoft stock prices using the Long Short Term Memory(LSTM).</h2>

<p>Long Short-Term Memory (LSTM) is a type of recurrent neural network (RNN) architecture that is designed to overcome the limitations of traditional RNNs when dealing with long-term dependencies in sequential data.</p>

<p>It was primarily introduced as a solution to the vanishiing gradient problem</p>
<h2>Domains in which LSTM is used:</h2>
<li>Time series prediction</li>
<li>Natural language Processin(NLP)</li>
<li>Speech recognition</li>
<li>Image captioning</li>
<br/>

<h2>Components of a LSTM</h2>
<li>Memory Cell (C): Responsible for storing information over long sequences. Can be updated, cleared, and read based on the signals from the gates.</li>
<li>Input Gate (I): Determines how much of the new information should be stored in the memory cell.</li>
<li>Forget Gate (F): Decides how much of the existing information in the memory cell should be discarded.</li>
<li>Output Gate (O): Controls how much of the memory cell content should be used to produce the output at the current time step.</li>
<br/>
<p>A LSTM is optimized using backpropagation through time (BPTT), a variant of standard backpropagation.</p>
