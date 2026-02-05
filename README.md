# App.htlm-SERVICIO-ESTRAT-GICO-DE-GERENCIA- # 🌐 Plataforma Social "Alpha-X"
**Gerencia General: Enrique Argeo Daza**

Este repositorio es la sede oficial del desarrollo. Se ha establecido la arquitectura base fusionando la velocidad de **Telegram X**, la dinámica de **X.com** y la libertad de video de **Rumble**.

---

## 📊 Informe de Gerencia
- **ID de Proyecto:** App-Alpha
- **Estado:** 🟠 Subsanando errores de nomenclatura (Pasando de .htlm a .html)
- **Líder:** Enrique Argeo Daza

## 🛠️ Especificaciones Técnicas (Requeridas)
Para que la red social funcione, el sistema debe contar con los siguientes archivos en la raíz:
1.  **`App.html`** (El núcleo de la aplicación).
2.  **`style.css`** (El diseño oscuro y moderno).

## 🚀 Hoja de Ruta Inmediata
- [X] Creación de repositorio de respaldo.
- [ ] Renombrar archivos críticos para despliegue.
- [ ] Implementación de la interfaz de Video-Streaming.
- [ ] Configuración del chat de mensajería instantánea.

---
*Documento verificado y aprobado por la Gerencia General.* <!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MUNDO DE LA GENTE MRQ | Oficial</title>
    <link rel="stylesheet" href="style.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
</head>
<body>

    <header class="mrq-header">
        <div class="logo-area">
            <span class="logo-text">MUNDO DE LA GENTE <span class="badge">MRQ</span></span>
        </div>
        <div class="search-bar">
            <input type="text" placeholder="Buscar en el Mundo MRQ...">
        </div>
        <div class="header-tools">
            <button class="btn-live"><i class="fas fa-satellite-dish"></i> EN VIVO</button>
            <i class="fas fa-paper-plane"></i>
            <i class="fas fa-bell"></i>
            <div class="user-profile">EA</div>
        </div>
    </header>

    <div class="layout">
        <aside class="sidebar-chats">
            <h3>Mensajería MRQ</h3>
            <div class="chat-box active">
                <i class="fas fa-bullhorn"></i> Canal Oficial MRQ
            </div>
            <div class="chat-box">
                <i class="fas fa-video"></i> Transmisiones Rumble
            </div>
            <div class="chat-box">
                <i class="fas fa-users"></i> Comunidad Global
            </div>
        </aside>

        <main class="feed-area">
            <div class="post-box">
                <textarea placeholder="¿Qué hay de nuevo en el Mundo de la Gente?"></textarea>
                <div class="post-footer">
                    <div class="media-icons">
                        <i class="fas fa-image"></i>
                        <i class="fas fa-video"></i>
                        <i class="fas fa-microphone"></i>
                    </div>
                    <button class="btn-send">Publicar MRQ</button>
                </div>
            </div>

            <article class="mrq-post">
                <div class="post-header">
                    <strong>Enrique Argeo Daza</strong> <span>@GerenciaGeneral</span>
                </div>
                <div class="video-rumble">
                    <div class="play-overlay"><i class="fas fa-play"></i></div>
                    <img src="https://via.placeholder.com/800x450/0f1419/ffffff?text=MUNDO+DE+LA+GENTE+MRQ+VIDEO" alt="Video">
                </div>
                <div class="post-actions">
                    <span><i class="far fa-heart"></i> 5k</span>
                    <span><i class="far fa-comment"></i> 800</span>
                    <span><i class="fas fa-retweet"></i> 200</span>
                </div>
            </article>
        </main>

        <aside class="sidebar-trends">
            <h3>Tendencias MRQ</h3>
            <div class="trend">#GenteUnida</div>
            <div class="trend">#MRQ_Oficial</div>
            <div class="trend">#EnriqueArgeo</div>
        </aside>
    </div>

</body>
</html> :root {
    --mrq-dark: #000000;
    --mrq-accent: #0088cc; /* Azul Telegram X */
    --mrq-text: #ffffff;
    --mrq-gray: #16181c; /* Gris X.com */
}

body {
    background-color: var(--mrq-dark);
    color: var(--mrq-text);
    margin: 0;
    font-family: 'Helvetica', Arial, sans-serif;
}

.mrq-header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 10px 40px;
    border-bottom: 1px solid #333;
    background: var(--mrq-dark);
    position: sticky;
    top: 0;
}

.logo-text { font-weight: bold; font-size: 1.2rem; }
.badge { background: var(--mrq-accent); padding: 2px 6px; border-radius: 4px; font-size: 0.8rem; }

.layout { display: grid; grid-template-columns: 260px 1fr 300px; gap: 20px; max-width: 1400px; margin: 0 auto; }

.chat-box { padding: 15px; cursor: pointer; border-radius: 8px; margin: 5px; }
.chat-box.active { background: #1a2733; border-left: 4px solid var(--mrq-accent); }

.post-box { background: var(--mrq-gray); padding: 15px; border-radius: 12px; margin-top: 20px; }
textarea { width: 100%; background: transparent; border: none; color: white; resize: none; font-size: 1.1rem; }

.btn-send { background: var(--mrq-accent); color: white; border: none; padding: 10px 20px; border-radius: 20px; cursor: pointer; font-weight: bold; }

.video-rumble { position: relative; width: 100%; background: #000; border-radius: 12px; overflow: hidden; margin-top: 10px; }
.play-overlay { position: absolute; top: 50%; left: 50%; transform: translate(-50%, -50%); font-size: 4rem; color: rgba(255,255,255,0.8); }
:root {
    --mrq-dark: #000000;
    --mrq-accent: #0088cc; /* Azul Telegram X */
    --mrq-text: #ffffff;
    --mrq-gray: #16181c; /* Gris X.com */
}

body {
    background-color: var(--mrq-dark);
    color: var(--mrq-text);
    margin: 0;
    font-family: 'Helvetica', Arial, sans-serif;
}

.mrq-header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 10px 40px;
    border-bottom: 1px solid #333;
    background: var(--mrq-dark);
    position: sticky;
    top: 0;
}

.logo-text { font-weight: bold; font-size: 1.2rem; }
.badge { background: var(--mrq-accent); padding: 2px 6px; border-radius: 4px; font-size: 0.8rem; }

.layout { display: grid; grid-template-columns: 260px 1fr 300px; gap: 20px; max-width: 1400px; margin: 0 auto; }

.chat-box { padding: 15px; cursor: pointer; border-radius: 8px; margin: 5px; }
.chat-box.active { background: #1a2733; border-left: 4px solid var(--mrq-accent); }

.post-box { background: var(--mrq-gray); padding: 15px; border-radius: 12px; margin-top: 20px; }
textarea { width: 100%; background: transparent; border: none; color: white; resize: none; font-size: 1.1rem; }

.btn-send { background: var(--mrq-accent); color: white; border: none; padding: 10px 20px; border-radius: 20px; cursor: pointer; font-weight: bold; }

.video-rumble { position: relative; width: 100%; background: #000; border-radius: 12px; overflow: hidden; margin-top: 10px; }
.play-overlay { position: absolute; top: 50%; left: 50%; transform: translate(-50%, -50%); font-size: 4rem; color: rgba(255,255,255,0.8); }


