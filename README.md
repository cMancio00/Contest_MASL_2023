# Contest Multivariate Analysis and Statistical Learning 2023
**Autore**:
- [Christian Mancini](https://github.com/cMancio00)

# Multi Sample Splitting

Utilizzare il kernel descritto in seguito per eseguire il [Notebook](/MultiSampleSplitting.ipynb).
## Installazione dei requisiti per la riproduzione dei risultati.

### Creazione dell' Ambiente Virtuale nella cartella cartella `.venv`

```bash
python3 -m venv .venv
```

> Si consiglia di essere nella cartella di progetto per un'organizzazione più efficiente.
>> Avendo specificato un nome nascosto, il nome dell' ambiente Virtuale sarà il nome della cartella del progetto,
>> in questo caso `Contest_MASL_2023`

### Collegare l' Ambiente Virtuale ad un Kernel di Jupyter

#### Attivare l'ambiente

```bash
source .venv/bin/activate
```
#### Installare il kernel di jupyter
```bash
pip install ipykernel
```

#### Aggingere l'ambiente virtuale a jupyter con 

```bash
python -Xfrozen_modules=off -m ipykernel install --user --name=Contest_MASL_2023
```
Stampando la lista dei kernel dovremmo ottenere il seguente risultato:

```bash
jupyter kernelspec list
```

```
0.00s - Debugger warning: It seems that frozen modules are being used, which may
0.00s - make the debugger miss breakpoints. Please pass -Xfrozen_modules=off
0.00s - to python to disable frozen modules.
0.00s - Note: Debugging will proceed. Set PYDEVD_DISABLE_FILE_VALIDATION=1 to disable this validation.
Available kernels:
  contest_masl_2023    /home/mancio/.local/share/jupyter/kernels/contest_masl_2023
  python3              /home/mancio/.local/share/jupyter/kernels/python3

```

### Installazione delle dipendenze
```bash
pip install --upgrade pip & pip install -r requirements.txt
```

