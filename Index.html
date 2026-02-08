index.html](https://github.com/user-attachments/files/25162114/worduel-final-demo.1.html)
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Worduel - Complete Demo</title>
    <link href="https://fonts.googleapis.com/css2?family=JetBrains+Mono:wght@400;700;900&family=Inter:wght@400;600;700;900&display=swap" rel="stylesheet">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        :root {
            --bg-primary: #0a0e14;
            --bg-secondary: #151922;
            --bg-elevated: #222831;
            --neon-green: #00ff88;
            --neon-yellow: #ffd60a;
            --neon-cyan: #00d9ff;
            --neon-red: #ff3366;
            --neon-purple: #a855f7;
            --correct: #00ff88;
            --present: #ffd60a;
            --absent: #2d3748;
            --border-primary: #2d3748;
            --text-primary: #e5e7eb;
            --text-secondary: #9ca3af;
            --text-muted: #6b7280;
            --glow-green: 0 0 20px rgba(0, 255, 136, 0.4);
            --shadow-lg: 0 10px 40px rgba(0, 0, 0, 0.5);
        }

        body {
            font-family: 'Inter', sans-serif;
            background: var(--bg-primary);
            color: var(--text-primary);
            min-height: 100vh;
            overflow-x: hidden;
        }

        body::before {
            content: '';
            position: fixed;
            inset: 0;
            background: 
                linear-gradient(90deg, rgba(0, 255, 136, 0.02) 1px, transparent 1px),
                linear-gradient(0deg, rgba(0, 255, 136, 0.02) 1px, transparent 1px);
            background-size: 40px 40px;
            pointer-events: none;
        }

        .screen {
            display: none;
        }

        .screen.active {
            display: block;
        }

        /* ===== SPLASH SCREEN ===== */
        .splash-screen {
            position: fixed;
            inset: 0;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            z-index: 10000;
        }

        .splash-screen.active {
            display: flex;
        }

        .splash-logo {
            font-size: 100px;
            margin-bottom: 20px;
            animation: float 3s ease-in-out infinite;
            filter: drop-shadow(var(--glow-green));
        }

        @keyframes float {
            0%, 100% { transform: translateY(0); }
            50% { transform: translateY(-15px); }
        }

        .splash-title {
            font-size: 64px;
            font-weight: 900;
            letter-spacing: -2px;
            margin-bottom: 12px;
            background: linear-gradient(135deg, var(--neon-green), var(--neon-cyan));
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }

        .splash-subtitle {
            font-size: 16px;
            color: var(--text-secondary);
            text-transform: uppercase;
            letter-spacing: 3px;
            margin-bottom: 40px;
        }

        .loading-bar {
            width: 280px;
            height: 4px;
            background: var(--bg-secondary);
            border-radius: 2px;
            overflow: hidden;
            margin-bottom: 12px;
        }

        .loading-progress {
            height: 100%;
            background: linear-gradient(90deg, var(--neon-green), var(--neon-cyan));
            width: 0%;
            animation: load 2s ease forwards;
            box-shadow: var(--glow-green);
        }

        @keyframes load {
            to { width: 100%; }
        }

        .splash-timer {
            font-family: 'JetBrains Mono', monospace;
            font-size: 14px;
            color: var(--text-muted);
            margin-top: 8px;
        }

        .splash-credit {
            position: absolute;
            bottom: 32px;
            font-size: 12px;
            color: var(--text-muted);
        }

        /* ===== HOME SCREEN ===== */
        .home-container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 40px 20px;
        }

        .home-header {
            text-align: center;
            margin-bottom: 48px;
        }

        .home-logo {
            font-size: 72px;
            margin-bottom: 12px;
            filter: drop-shadow(var(--glow-green));
        }

        .home-title {
            font-size: 48px;
            font-weight: 900;
            letter-spacing: -1px;
            margin-bottom: 8px;
            background: linear-gradient(135deg, var(--neon-green), var(--neon-cyan));
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }

        .home-tagline {
            font-size: 14px;
            color: var(--text-secondary);
            text-transform: uppercase;
            letter-spacing: 2px;
        }

        .stats-display {
            background: var(--bg-secondary);
            border: 1px solid var(--border-primary);
            border-radius: 16px;
            padding: 28px;
            margin-bottom: 40px;
            box-shadow: var(--shadow-lg);
        }

        .stats-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(180px, 1fr));
            gap: 20px;
        }

        .stat-card {
            text-align: center;
            padding: 16px;
            background: var(--bg-primary);
            border: 1px solid var(--border-primary);
            border-radius: 10px;
        }

        .stat-icon {
            font-size: 28px;
            margin-bottom: 6px;
        }

        .stat-value {
            font-size: 28px;
            font-weight: 900;
            color: var(--neon-green);
            font-family: 'JetBrains Mono', monospace;
            margin-bottom: 4px;
        }

        .stat-label {
            font-size: 11px;
            color: var(--text-muted);
            text-transform: uppercase;
            letter-spacing: 0.5px;
        }

        .modes-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 20px;
        }

        .mode-card {
            background: var(--bg-secondary);
            border: 2px solid var(--border-primary);
            border-radius: 14px;
            padding: 28px;
            cursor: pointer;
            transition: all 0.3s;
            box-shadow: var(--shadow-lg);
        }

        .mode-card:hover {
            border-color: var(--neon-green);
            transform: translateY(-4px);
            box-shadow: 0 0 25px rgba(0, 255, 136, 0.2);
        }

        .mode-card.blitz {
            border-color: rgba(255, 214, 10, 0.3);
        }

        .mode-card.blitz:hover {
            border-color: var(--neon-yellow);
            box-shadow: 0 0 25px rgba(255, 214, 10, 0.2);
        }

        .mode-card.training {
            border-color: rgba(168, 85, 247, 0.3);
        }

        .mode-card.training:hover {
            border-color: var(--neon-purple);
            box-shadow: 0 0 25px rgba(168, 85, 247, 0.2);
        }

        .mode-icon {
            font-size: 40px;
            margin-bottom: 12px;
        }

        .mode-name {
            font-size: 24px;
            font-weight: 900;
            margin-bottom: 6px;
        }

        .mode-desc {
            color: var(--text-secondary);
            font-size: 13px;
            margin-bottom: 14px;
            line-height: 1.5;
        }

        .mode-details {
            display: flex;
            flex-wrap: wrap;
            gap: 8px;
            margin-top: 16px;
        }

        .mode-tag {
            background: var(--bg-primary);
            border: 1px solid var(--border-primary);
            padding: 5px 10px;
            border-radius: 5px;
            font-size: 10px;
            text-transform: uppercase;
            letter-spacing: 0.5px;
            color: var(--text-muted);
            font-family: 'JetBrains Mono', monospace;
        }

        /* ===== GAME SCREEN ===== */
        .game-container {
            max-width: 1400px;
            margin: 0 auto;
            padding: 20px;
        }

        .game-header {
            background: var(--bg-secondary);
            border: 1px solid var(--border-primary);
            border-radius: 12px;
            padding: 16px 24px;
            margin-bottom: 18px;
            display: flex;
            justify-content: space-between;
            align-items: center;
            box-shadow: var(--shadow-lg);
        }

        .game-info {
            display: flex;
            align-items: center;
            gap: 16px;
        }

        .mode-badge {
            background: var(--bg-primary);
            border: 1px solid var(--neon-green);
            padding: 7px 14px;
            border-radius: 6px;
            font-family: 'JetBrains Mono', monospace;
            font-size: 11px;
            color: var(--neon-green);
            text-transform: uppercase;
            letter-spacing: 0.5px;
        }

        .timer-display {
            font-family: 'JetBrains Mono', monospace;
            font-size: 22px;
            font-weight: 900;
            color: var(--neon-green);
        }

        .timer-display.warning {
            color: var(--neon-yellow);
            animation: pulse 1s infinite;
        }

        .timer-display.danger {
            color: var(--neon-red);
        }

        @keyframes pulse {
            0%, 100% { opacity: 1; }
            50% { opacity: 0.5; }
        }

        .round-display {
            font-family: 'JetBrains Mono', monospace;
            font-size: 13px;
            color: var(--text-secondary);
        }

        .home-btn {
            padding: 7px 14px;
            background: transparent;
            border: 1px solid var(--border-primary);
            color: var(--text-secondary);
            border-radius: 6px;
            cursor: pointer;
            font-size: 11px;
            font-weight: 600;
            transition: all 0.2s;
            text-transform: uppercase;
            letter-spacing: 0.5px;
        }

        .home-btn:hover {
            border-color: var(--neon-cyan);
            color: var(--neon-cyan);
        }

        .battle-grid {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 18px;
            margin-bottom: 18px;
        }

        .player-panel {
            background: var(--bg-secondary);
            border: 1px solid var(--border-primary);
            border-radius: 12px;
            padding: 20px;
            box-shadow: var(--shadow-lg);
            position: relative;
        }

        .player-panel.you {
            border-color: var(--neon-green);
            box-shadow: 0 0 20px rgba(0, 255, 136, 0.12);
        }

        .player-panel.you::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            height: 3px;
            background: linear-gradient(90deg, var(--neon-green), transparent);
            border-radius: 12px 12px 0 0;
        }

        .panel-header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            margin-bottom: 16px;
            padding-bottom: 12px;
            border-bottom: 1px solid var(--border-primary);
        }

        .panel-title {
            font-size: 13px;
            font-weight: 700;
            color: var(--text-secondary);
            text-transform: uppercase;
            letter-spacing: 0.8px;
        }

        .panel-title.you {
            color: var(--neon-green);
        }

        .panel-score {
            font-size: 20px;
            font-weight: 900;
            color: var(--neon-green);
            font-family: 'JetBrains Mono', monospace;
        }

        .word-grid {
            display: flex;
            flex-direction: column;
            gap: 5px;
        }

        .word-row {
            display: flex;
            gap: 5px;
            justify-content: center;
        }

        .tile {
            width: 52px;
            height: 52px;
            background: var(--bg-primary);
            border: 2px solid var(--border-primary);
            border-radius: 7px;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 24px;
            font-weight: 900;
            font-family: 'JetBrains Mono', monospace;
            transition: all 0.15s cubic-bezier(0.16, 1, 0.3, 1);
        }

        .tile.filled {
            border-color: var(--text-muted);
            transform: scale(1.05);
        }

        .tile.correct {
            background: var(--correct);
            border-color: var(--correct);
            color: var(--bg-primary);
            box-shadow: 0 0 14px rgba(0, 255, 136, 0.3);
            animation: flip 0.4s cubic-bezier(0.16, 1, 0.3, 1);
        }

        .tile.present {
            background: var(--present);
            border-color: var(--present);
            color: var(--bg-primary);
            box-shadow: 0 0 14px rgba(255, 214, 10, 0.3);
            animation: flip 0.4s cubic-bezier(0.16, 1, 0.3, 1);
        }

        .tile.absent {
            background: var(--absent);
            border-color: var(--absent);
            color: var(--text-muted);
            animation: flip 0.4s cubic-bezier(0.16, 1, 0.3, 1);
        }

        @keyframes flip {
            0% { transform: rotateX(0); }
            50% { transform: rotateX(90deg); }
            100% { transform: rotateX(0); }
        }

        .keyboard {
            background: var(--bg-secondary);
            border: 1px solid var(--border-primary);
            border-radius: 12px;
            padding: 18px;
            box-shadow: var(--shadow-lg);
        }

        .keyboard-row {
            display: flex;
            gap: 5px;
            justify-content: center;
            margin-bottom: 5px;
        }

        .key {
            background: var(--bg-primary);
            border: 1px solid var(--border-primary);
            color: var(--text-primary);
            padding: 14px;
            border-radius: 6px;
            min-width: 42px;
            font-weight: 700;
            cursor: pointer;
            font-size: 13px;
            transition: all 0.15s;
            user-select: none;
            font-family: 'JetBrains Mono', monospace;
        }

        .key:hover {
            background: var(--bg-elevated);
            border-color: var(--text-muted);
            transform: translateY(-2px);
        }

        .key:active {
            transform: translateY(0);
        }

        .key.wide {
            min-width: 65px;
            font-size: 11px;
        }

        .key.correct {
            background: var(--correct);
            border-color: var(--correct);
            color: var(--bg-primary);
            box-shadow: 0 0 10px rgba(0, 255, 136, 0.3);
        }

        .key.present {
            background: var(--present);
            border-color: var(--present);
            color: var(--bg-primary);
            box-shadow: 0 0 10px rgba(255, 214, 10, 0.3);
        }

        .key.absent {
            background: var(--absent);
            border-color: var(--absent);
            color: var(--text-muted);
        }

        /* ===== RESULT MODAL ===== */
        .result-modal {
            display: none;
            position: fixed;
            inset: 0;
            background: rgba(10, 14, 20, 0.95);
            backdrop-filter: blur(8px);
            align-items: center;
            justify-content: center;
            z-index: 9999;
        }

        .result-modal.active {
            display: flex;
        }

        .result-container {
            background: var(--bg-secondary);
            border: 1px solid var(--border-primary);
            border-radius: 14px;
            padding: 40px;
            max-width: 460px;
            text-align: center;
            box-shadow: var(--shadow-lg);
            animation: modalSlide 0.4s cubic-bezier(0.16, 1, 0.3, 1);
        }

        @keyframes modalSlide {
            from {
                opacity: 0;
                transform: translateY(-30px) scale(0.95);
            }
        }

        .result-icon {
            font-size: 72px;
            margin-bottom: 20px;
            animation: resultPulse 0.6s ease;
        }

        @keyframes resultPulse {
            0%, 100% { transform: scale(1); }
            50% { transform: scale(1.12); }
        }

        .result-title {
            font-size: 32px;
            font-weight: 900;
            margin-bottom: 20px;
            letter-spacing: -0.5px;
        }

        .result-title.win {
            color: var(--neon-green);
            text-shadow: var(--glow-green);
        }

        .result-title.lose {
            color: var(--text-secondary);
        }

        .result-stats-grid {
            background: var(--bg-primary);
            border: 1px solid var(--border-primary);
            border-radius: 10px;
            padding: 20px;
            margin: 20px 0;
        }

        .result-stat-row {
            display: flex;
            justify-content: space-between;
            padding: 10px 0;
            font-family: 'JetBrains Mono', monospace;
        }

        .result-stat-row:not(:last-child) {
            border-bottom: 1px solid var(--border-primary);
        }

        .result-stat-label {
            color: var(--text-muted);
            font-size: 11px;
            text-transform: uppercase;
            letter-spacing: 0.5px;
        }

        .result-stat-value {
            font-size: 16px;
            font-weight: 700;
        }

        .result-stat-value.positive {
            color: var(--neon-green);
        }

        .result-actions {
            display: flex;
            gap: 10px;
            margin-top: 26px;
        }

        .result-btn {
            flex: 1;
            padding: 13px;
            border: none;
            border-radius: 7px;
            font-weight: 700;
            cursor: pointer;
            transition: all 0.2s;
            text-transform: uppercase;
            letter-spacing: 0.5px;
            font-size: 12px;
        }

        .result-btn.primary {
            background: var(--neon-green);
            color: var(--bg-primary);
        }

        .result-btn.primary:hover {
            transform: translateY(-2px);
            box-shadow: var(--glow-green);
        }

        .result-btn.secondary {
            background: transparent;
            border: 1px solid var(--border-primary);
            color: var(--text-secondary);
        }

        .result-btn.secondary:hover {
            border-color: var(--text-primary);
            color: var(--text-primary);
        }

        @media (max-width: 1024px) {
            .battle-grid {
                grid-template-columns: 1fr;
            }
        }

        @media (max-width: 768px) {
            .tile {
                width: 45px;
                height: 45px;
                font-size: 20px;
            }
            .key {
                padding: 11px;
                min-width: 34px;
                font-size: 12px;
            }
        }
    </style>
</head>
<body>
    <!-- SPLASH SCREEN -->
    <div class="screen active splash-screen" id="splashScreen">
        <div class="splash-logo">⚔️</div>
        <h1 class="splash-title">WORDUEL</h1>
        <p class="splash-subtitle">Competitive Word Battle</p>
        <div class="loading-bar">
            <div class="loading-progress"></div>
        </div>
        <p class="splash-timer" id="splashTimer">Loading... 3s</p>
        <p class="splash-credit">🎮 APLAY STUDIOS</p>
    </div>

    <!-- HOME SCREEN -->
    <div class="screen" id="homeScreen">
        <div class="home-container">
            <div class="home-header">
                <div class="home-logo">⚔️</div>
                <h1 class="home-title">WORDUEL</h1>
                <p class="home-tagline">Choose Your Battle Mode</p>
            </div>

            <div class="stats-display">
                <div class="stats-grid">
                    <div class="stat-card">
                        <div class="stat-icon">🎮</div>
                        <div class="stat-value" id="totalGames">0</div>
                        <div class="stat-label">Games Played</div>
                    </div>
                    <div class="stat-card">
                        <div class="stat-icon">🏆</div>
                        <div class="stat-value" id="totalWins">0</div>
                        <div class="stat-label">Victories</div>
                    </div>
                    <div class="stat-card">
                        <div class="stat-icon">🔥</div>
                        <div class="stat-value" id="winStreak">0</div>
                        <div class="stat-label">Win Streak</div>
                    </div>
                    <div class="stat-card">
                        <div class="stat-icon">⭐</div>
                        <div class="stat-value" id="winRate">0%</div>
                        <div class="stat-label">Win Rate</div>
                    </div>
                </div>
            </div>

            <div class="modes-grid">
                <div class="mode-card" onclick="startMode('best-of-3')">
                    <div class="mode-icon">🏆</div>
                    <div class="mode-name">BEST OF 3</div>
                    <div class="mode-desc">First to win 2 rounds takes the match. Strategic gameplay with round-based scoring.</div>
                    <div class="mode-details">
                        <div class="mode-tag">⏱️ 3 min/round</div>
                        <div class="mode-tag">🎯 ranked</div>
                        <div class="mode-tag">🔥 competitive</div>
                    </div>
                </div>

                <div class="mode-card blitz" onclick="startMode('blitz')">
                    <div class="mode-icon">⚡</div>
                    <div class="mode-name">BLITZ</div>
                    <div class="mode-desc">5-minute speed challenge. Solve as many words as possible before time runs out!</div>
                    <div class="mode-details">
                        <div class="mode-tag">⏱️ 5 minutes</div>
                        <div class="mode-tag">🚀 speed</div>
                        <div class="mode-tag">🔄 unlimited</div>
                    </div>
                </div>

                <div class="mode-card training" onclick="startMode('training')">
                    <div class="mode-icon">🎓</div>
                    <div class="mode-name">TRAINING</div>
                    <div class="mode-desc">Practice mode with no time limit. Perfect your strategy and learn new words.</div>
                    <div class="mode-details">
                        <div class="mode-tag">⏱️ no timer</div>
                        <div class="mode-tag">🎯 practice</div>
                        <div class="mode-tag">😌 casual</div>
                    </div>
                </div>
            </div>
        </div>
    </div>

    <!-- GAME SCREEN -->
    <div class="screen" id="gameScreen">
        <div class="game-container">
            <div class="game-header">
                <div class="game-info">
                    <div class="mode-badge" id="currentMode">BEST OF 3</div>
                    <div class="timer-display" id="timer">3:00</div>
                    <div class="round-display" id="roundInfo">ROUND 1 OF 3</div>
                </div>
                <button class="home-btn" onclick="goHome()">HOME</button>
            </div>

            <div class="battle-grid">
                <div class="player-panel you">
                    <div class="panel-header">
                        <span class="panel-title you">YOUR BOARD</span>
                        <span class="panel-score" id="yourScore">0</span>
                    </div>
                    <div class="word-grid" id="yourGrid"></div>
                </div>

                <div class="player-panel">
                    <div class="panel-header">
                        <span class="panel-title">AI OPPONENT</span>
                        <span class="panel-score" id="opponentScore">0</span>
                    </div>
                    <div class="word-grid" id="opponentGrid"></div>
                </div>
            </div>

            <div class="keyboard">
                <div class="keyboard-row">
                    <div class="key" data-key="Q">Q</div>
                    <div class="key" data-key="W">W</div>
                    <div class="key" data-key="E">E</div>
                    <div class="key" data-key="R">R</div>
                    <div class="key" data-key="T">T</div>
                    <div class="key" data-key="Y">Y</div>
                    <div class="key" data-key="U">U</div>
                    <div class="key" data-key="I">I</div>
                    <div class="key" data-key="O">O</div>
                    <div class="key" data-key="P">P</div>
                </div>
                <div class="keyboard-row">
                    <div class="key" data-key="A">A</div>
                    <div class="key" data-key="S">S</div>
                    <div class="key" data-key="D">D</div>
                    <div class="key" data-key="F">F</div>
                    <div class="key" data-key="G">G</div>
                    <div class="key" data-key="H">H</div>
                    <div class="key" data-key="J">J</div>
                    <div class="key" data-key="K">K</div>
                    <div class="key" data-key="L">L</div>
                </div>
                <div class="keyboard-row">
                    <div class="key wide" data-key="Enter">ENTER</div>
                    <div class="key" data-key="Z">Z</div>
                    <div class="key" data-key="X">X</div>
                    <div class="key" data-key="C">C</div>
                    <div class="key" data-key="V">V</div>
                    <div class="key" data-key="B">B</div>
                    <div class="key" data-key="N">N</div>
                    <div class="key" data-key="M">M</div>
                    <div class="key wide" data-key="Backspace">⌫</div>
                </div>
            </div>
        </div>
    </div>

    <!-- RESULT MODAL -->
    <div class="result-modal" id="resultModal">
        <div class="result-container">
            <div class="result-icon" id="resultIcon">🏆</div>
            <h2 class="result-title" id="resultTitle">VICTORY</h2>

            <div class="result-stats-grid" id="resultStats">
                <div class="result-stat-row">
                    <span class="result-stat-label">SOLUTION</span>
                    <span class="result-stat-value" id="resultWord">CRANE</span>
                </div>
                <div class="result-stat-row">
                    <span class="result-stat-label">YOUR GUESSES</span>
                    <span class="result-stat-value" id="yourGuesses">3</span>
                </div>
                <div class="result-stat-row">
                    <span class="result-stat-label">OPPONENT GUESSES</span>
                    <span class="result-stat-value" id="oppGuesses">4</span>
                </div>
            </div>

            <div class="result-actions">
                <button class="result-btn primary" id="playAgainBtn">PLAY AGAIN</button>
                <button class="result-btn secondary" onclick="goHome()">HOME</button>
            </div>
        </div>
    </div>

    <script>
        const WORDS = ['CRANE','SLATE','TRACE','STARE','RAISE','SHINE','STONE','BRAVE','GLOVE','PROVE','SHARE','SPARE','PHASE','SHAPE','GRAPE','TRADE','CHASE','HOUSE','MOUSE','PLACE','PLANT','PIANO','CRIME','PRIME','CLIMB','ROUND','SOUND','POUND','MOUNT','CLOUD','PROUD','FLOUR','WORLD','WORTH','WRITE','WRONG','WROTE','FRESH','FLESH','FLASH','TRASH','CRASH'];

        let stats = {
            totalGames: 0,
            totalWins: 0,
            currentStreak: 0
        };

        let currentMode = '';
        let game = {
            targetWord: '',
            currentGuess: '',
            currentRow: 0,
            yourGuesses: [],
            opponentGuesses: [],
            gameOver: false,
            yourWins: 0,
            opponentWins: 0,
            currentRound: 1,
            timeLeft: 0,
            timerInterval: null,
            opponentInterval: null,
            wordsCompleted: 0
        };

        // ===== SPLASH SCREEN TIMER =====
        let splashCountdown = 3;
        const splashTimerEl = document.getElementById('splashTimer');
        
        const splashInterval = setInterval(() => {
            splashCountdown--;
            splashTimerEl.textContent = `Loading... ${splashCountdown}s`;
            
            if (splashCountdown <= 0) {
                clearInterval(splashInterval);
                const splashScreen = document.getElementById('splashScreen');
                splashScreen.classList.remove('active');
                splashScreen.style.display = 'none'; // Completely hide splash
                document.getElementById('homeScreen').classList.add('active');
                loadStats();
            }
        }, 1000);

        // ===== STATS =====
        function loadStats() {
            const saved = localStorage.getItem('worduelStats');
            if (saved) {
                stats = JSON.parse(saved);
                updateStatsDisplay();
            }
        }

        function saveStats() {
            localStorage.setItem('worduelStats', JSON.stringify(stats));
        }

        function updateStatsDisplay() {
            document.getElementById('totalGames').textContent = stats.totalGames;
            document.getElementById('totalWins').textContent = stats.totalWins;
            document.getElementById('winStreak').textContent = stats.currentStreak;
            const winRate = stats.totalGames > 0 ? Math.round((stats.totalWins / stats.totalGames) * 100) : 0;
            document.getElementById('winRate').textContent = winRate + '%';
        }

        // ===== MODE SELECTION =====
        function startMode(mode) {
            currentMode = mode;
            document.getElementById('homeScreen').classList.remove('active');
            document.getElementById('gameScreen').classList.add('active');
            
            const modeNames = {
                'best-of-3': 'BEST OF 3',
                'blitz': 'BLITZ MODE',
                'training': 'TRAINING'
            };
            document.getElementById('currentMode').textContent = modeNames[mode];
            
            // Configure timer and info
            if (mode === 'best-of-3') {
                game.timeLeft = 180; // 3 minutes
                document.getElementById('roundInfo').textContent = 'ROUND 1 OF 3';
            } else if (mode === 'blitz') {
                game.timeLeft = 300; // 5 minutes
                document.getElementById('roundInfo').textContent = 'WORDS: 0';
            } else if (mode === 'training') {
                game.timeLeft = -1; // No timer
                document.getElementById('timer').textContent = '∞';
                document.getElementById('roundInfo').textContent = 'PRACTICE MODE';
            }
            
            startGame();
        }

        // ===== GAME LOGIC =====
        function startGame() {
            game.targetWord = WORDS[Math.floor(Math.random() * WORDS.length)];
            game.currentGuess = '';
            game.currentRow = 0;
            game.yourGuesses = [];
            game.opponentGuesses = [];
            game.gameOver = false;
            
            console.log('Target word:', game.targetWord);
            
            createGrid('yourGrid');
            createGrid('opponentGrid');
            setupKeyboard();
            
            if (game.timeLeft > 0) {
                startTimer();
            }
            
            startOpponent();
            
            document.getElementById('yourScore').textContent = game.yourWins;
            document.getElementById('opponentScore').textContent = game.opponentWins;
        }

        function startTimer() {
            if (game.timerInterval) clearInterval(game.timerInterval);
            
            game.timerInterval = setInterval(() => {
                game.timeLeft--;
                
                const minutes = Math.floor(game.timeLeft / 60);
                const seconds = game.timeLeft % 60;
                document.getElementById('timer').textContent = `${minutes}:${seconds.toString().padStart(2, '0')}`;
                
                const timerEl = document.getElementById('timer');
                if (game.timeLeft <= 30) {
                    timerEl.className = 'timer-display danger';
                } else if (game.timeLeft <= 60) {
                    timerEl.className = 'timer-display warning';
                } else {
                    timerEl.className = 'timer-display';
                }
                
                if (game.timeLeft <= 0) {
                    clearInterval(game.timerInterval);
                    endRound(false);
                }
            }, 1000);
        }

        function createGrid(id) {
            const grid = document.getElementById(id);
            grid.innerHTML = '';
            
            for (let i = 0; i < 6; i++) {
                const row = document.createElement('div');
                row.className = 'word-row';
                
                for (let j = 0; j < 5; j++) {
                    const tile = document.createElement('div');
                    tile.className = 'tile';
                    tile.id = `${id}-${i}-${j}`;
                    row.appendChild(tile);
                }
                
                grid.appendChild(row);
            }
        }

        function setupKeyboard() {
            document.querySelectorAll('.key').forEach(key => {
                key.onclick = () => handleKey(key.dataset.key);
                key.classList.remove('correct', 'present', 'absent');
            });
            
            document.onkeydown = (e) => {
                if (game.gameOver) return;
                if (e.key === 'Enter') handleKey('Enter');
                else if (e.key === 'Backspace') handleKey('Backspace');
                else if (/^[a-zA-Z]$/.test(e.key)) handleKey(e.key.toUpperCase());
            };
        }

        function handleKey(key) {
            if (game.gameOver) return;
            
            if (key === 'Enter' && game.currentGuess.length === 5) {
                submitGuess();
            } else if (key === 'Backspace' && game.currentGuess.length > 0) {
                game.currentGuess = game.currentGuess.slice(0, -1);
                updateCurrentRow();
            } else if (game.currentGuess.length < 5 && /^[A-Z]$/.test(key)) {
                game.currentGuess += key;
                updateCurrentRow();
            }
        }

        function updateCurrentRow() {
            for (let i = 0; i < 5; i++) {
                const tile = document.getElementById(`yourGrid-${game.currentRow}-${i}`);
                tile.textContent = i < game.currentGuess.length ? game.currentGuess[i] : '';
                tile.className = 'tile' + (i < game.currentGuess.length ? ' filled' : '');
            }
        }

        function evaluateGuess(guess, target) {
            const result = [];
            const targetLetters = target.split('');
            const used = new Array(5).fill(false);
            
            for (let i = 0; i < 5; i++) {
                if (guess[i] === targetLetters[i]) {
                    result[i] = 'correct';
                    used[i] = true;
                } else {
                    result[i] = null;
                }
            }
            
            for (let i = 0; i < 5; i++) {
                if (result[i] === null) {
                    const idx = targetLetters.findIndex((l, j) => l === guess[i] && !used[j]);
                    result[i] = idx !== -1 ? (used[idx] = true, 'present') : 'absent';
                }
            }
            
            return result;
        }

        function submitGuess() {
            const evaluation = evaluateGuess(game.currentGuess, game.targetWord);
            game.yourGuesses.push({word: game.currentGuess, eval: evaluation});
            
            revealTiles(evaluation, game.currentRow, 'yourGrid');
            updateKeyboard(game.currentGuess, evaluation);
            
            if (evaluation.every(e => e === 'correct')) {
                game.gameOver = true;
                
                if (currentMode === 'blitz') {
                    game.wordsCompleted++;
                    document.getElementById('roundInfo').textContent = `WORDS: ${game.wordsCompleted}`;
                    setTimeout(() => {
                        game.gameOver = false;
                        game.currentRow = 0;
                        game.yourGuesses = [];
                        game.opponentGuesses = [];
                        game.targetWord = WORDS[Math.floor(Math.random() * WORDS.length)];
                        createGrid('yourGrid');
                        createGrid('opponentGrid');
                        setupKeyboard();
                        console.log('New target:', game.targetWord);
                    }, 1000);
                } else {
                    setTimeout(() => endRound(true), 1500);
                }
            } else if (game.currentRow >= 5) {
                game.gameOver = true;
                setTimeout(() => endRound(false), 1500);
            } else {
                game.currentRow++;
                game.currentGuess = '';
            }
        }

        function revealTiles(evaluation, row, grid) {
            evaluation.forEach((status, i) => {
                setTimeout(() => {
                    const tile = document.getElementById(`${grid}-${row}-${i}`);
                    tile.classList.add(status);
                }, i * 140);
            });
        }

        function updateKeyboard(guess, evaluation) {
            guess.split('').forEach((letter, i) => {
                const key = document.querySelector(`[data-key="${letter}"]`);
                const status = evaluation[i];
                
                if (status === 'correct') {
                    key.classList.remove('present', 'absent');
                    key.classList.add('correct');
                } else if (status === 'present' && !key.classList.contains('correct')) {
                    key.classList.remove('absent');
                    key.classList.add('present');
                } else if (status === 'absent' && !key.classList.contains('correct') && !key.classList.contains('present')) {
                    key.classList.add('absent');
                }
            });
        }

        function startOpponent() {
            if (game.opponentInterval) clearInterval(game.opponentInterval);
            
            const makeGuess = () => {
                if (game.gameOver || game.opponentGuesses.length >= 6) return;
                
                const word = Math.random() < 0.22 ? game.targetWord : WORDS[Math.floor(Math.random() * WORDS.length)];
                const eval = evaluateGuess(word, game.targetWord);
                game.opponentGuesses.push({word, eval});
                
                const row = game.opponentGuesses.length - 1;
                
                for (let i = 0; i < 5; i++) {
                    setTimeout(() => {
                        const tile = document.getElementById(`opponentGrid-${row}-${i}`);
                        tile.textContent = '';
                        tile.classList.add('filled');
                    }, i * 90);
                }
                
                setTimeout(() => revealTiles(eval, row, 'opponentGrid'), 450);
                
                if (eval.every(e => e === 'correct')) {
                    if (!game.gameOver) {
                        game.gameOver = true;
                        setTimeout(() => endRound(false), 1500);
                    }
                }
            };
            
            setTimeout(makeGuess, 7000 + Math.random() * 3000);
            game.opponentInterval = setInterval(makeGuess, 11000 + Math.random() * 7000);
        }

        function endRound(youWon) {
            if (game.timerInterval) clearInterval(game.timerInterval);
            if (game.opponentInterval) clearInterval(game.opponentInterval);
            
            if (currentMode === 'best-of-3') {
                if (youWon) {
                    game.yourWins++;
                } else {
                    game.opponentWins++;
                }
                
                document.getElementById('yourScore').textContent = game.yourWins;
                document.getElementById('opponentScore').textContent = game.opponentWins;
                
                if (game.yourWins >= 2 || game.opponentWins >= 2) {
                    showFinalResult(game.yourWins > game.opponentWins);
                } else {
                    game.currentRound++;
                    document.getElementById('roundInfo').textContent = `ROUND ${game.currentRound} OF 3`;
                    setTimeout(() => {
                        game.timeLeft = 180;
                        startGame();
                    }, 2000);
                }
            } else if (currentMode === 'blitz') {
                showFinalResult(true);
            } else {
                showResult(youWon);
            }
        }

        function showResult(won) {
            document.getElementById('resultIcon').textContent = won ? '🏆' : '💀';
            const resultTitle = document.getElementById('resultTitle');
            resultTitle.textContent = won ? 'VICTORY' : 'DEFEAT';
            resultTitle.className = 'result-title ' + (won ? 'win' : 'lose');
            
            document.getElementById('resultWord').textContent = game.targetWord;
            document.getElementById('yourGuesses').textContent = game.yourGuesses.length;
            document.getElementById('oppGuesses').textContent = game.opponentGuesses.length;
            
            document.getElementById('playAgainBtn').onclick = () => {
                document.getElementById('resultModal').classList.remove('active');
                startGame();
            };
            
            document.getElementById('resultModal').classList.add('active');
        }

        function showFinalResult(won) {
            stats.totalGames++;
            if (won) {
                stats.totalWins++;
                stats.currentStreak++;
            } else {
                stats.currentStreak = 0;
            }
            saveStats();
            updateStatsDisplay();
            
            document.getElementById('resultIcon').textContent = won ? '🏆' : '💀';
            const resultTitle = document.getElementById('resultTitle');
            
            if (currentMode === 'blitz') {
                resultTitle.textContent = `${game.wordsCompleted} WORDS!`;
                resultTitle.className = 'result-title win';
                document.getElementById('resultStats').innerHTML = `
                    <div class="result-stat-row">
                        <span class="result-stat-label">WORDS SOLVED</span>
                        <span class="result-stat-value positive">${game.wordsCompleted}</span>
                    </div>
                    <div class="result-stat-row">
                        <span class="result-stat-label">FINAL WORD</span>
                        <span class="result-stat-value">${game.targetWord}</span>
                    </div>
                `;
            } else {
                resultTitle.textContent = won ? 'MATCH WON!' : 'MATCH LOST';
                resultTitle.className = 'result-title ' + (won ? 'win' : 'lose');
                document.getElementById('resultWord').textContent = game.targetWord;
                document.getElementById('yourGuesses').textContent = game.yourWins;
                document.getElementById('oppGuesses').textContent = game.opponentWins;
            }
            
            document.getElementById('playAgainBtn').onclick = () => {
                document.getElementById('resultModal').classList.remove('active');
                game.yourWins = 0;
                game.opponentWins = 0;
                game.currentRound = 1;
                game.wordsCompleted = 0;
                startMode(currentMode);
            };
            
            document.getElementById('resultModal').classList.add('active');
        }

        function goHome() {
            if (game.timerInterval) clearInterval(game.timerInterval);
            if (game.opponentInterval) clearInterval(game.opponentInterval);
            
            document.getElementById('gameScreen').classList.remove('active');
            document.getElementById('resultModal').classList.remove('active');
            document.getElementById('homeScreen').classList.add('active');
            
            game.yourWins = 0;
            game.opponentWins = 0;
            game.currentRound = 1;
            game.wordsCompleted = 0;
        }
    </script>
</body>
</html>
