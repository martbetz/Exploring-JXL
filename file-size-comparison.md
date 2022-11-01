<div align="center"><h1>File-Size Comparison Test</h1></div>

```mermaid 
    graph TD
    A["<b>RAF</b><br>(unprocessed)<br>4896 x 3264<br><b>33.79 MB</b>"] -- " RawTherapee " --> B["8-bit <b>PNG</b><br>(lossless)<br>1800 x 1200<br><b>3.87 MB</b>"]

    A["<b>RAF</b><br>(unprocessed)<br>4896x 3264<br><b>33.79 MB</b>"] -- " RawTherapee " --> C["<b>TIF</b><br>(lossless)<br>1800 x 1200<br><b>33.79 MB</b>"]
    A["<b>RAF</b><br>(unprocessed)<br>4896 x 3264<br><b>33.79 MB</b>"] -- " RawTherapee " --> D["8-bit <b>JPG</b><br>(lossy)<br>1800 x 1200 <br><b>2.35 MB</b>"]
    
    C["8-bit <b>TIF</b><br>(lossless)<br>1800 x 1200<br><b>6.38 MB</b>"] -- Krita --> E["8-bit <b>JXL</b><br>(lossless) <br>1800 x 1200<br><b>2.19 MB</b>"]
    
    C["8-bit <b>TIF</b><br>(lossless)<br>1800 x 1200<br><b>6.38 MB</b>"] -- Krita --> F["8-bit <b>JXL</b><br>(lossy)<br>1800 x 1200<br> <b>0.93 MB</b>"]

    subgraph " "
    F["8-bit <b>JXL</b><br>(lossy)<br>1800 x 1200<br> <b>0.93 MB</b>"]
    D["8-bit <b>JPG</b><br>(lossy)<br>1800 x 1200 <br><b>2.35 MB</b>"]
    end
    subgraph " "
    E["8-bit <b>JXL</b><br>(lossless) <br>1800 x 1200<br><b>2.19 MB</b>"]
    B["8-bit <b>PNG</b><br>(lossless)<br>1800 x 1200<br><b>3.87 MB</b>"]
    end
```

<div align="center">All image formats were processed at the highest quality settings.</div>