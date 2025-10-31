<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>OQCRP 官方前旗县角色扮演 - 官网</title>
    <style>
        body {
            background-color: #fff;
            color: #333;
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
        .header {
            background-color: #4285f4;
            color: white;
            padding: 1rem 2rem;
            text-align: center;
            position: relative;
        }
        .lang-selector {
            position: absolute;
            top: 1rem;
            right: 2rem;
            background-color: rgba(255,255,255,0.2);
            color: white;
            border: none;
            padding: 0.5rem;
            border-radius: 3px;
            cursor: pointer;
            font-size: 0.9rem;
            transition: background-color 0.3s;
        }
        .lang-selector:hover {
            background-color: rgba(255,255,255,0.3);
        }
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 2rem;
        }
        .banner {
            background: url("https://images.weserv.nl/?url=https://picsum.photos/id/1039/1200/400") no-repeat center;
            background-size: cover;
            height: 300px;
            display: flex;
            align-items: center;
            justify-content: center;
            margin-bottom: 2rem;
            border-radius: 3px;
        }
        .banner-text {
            background-color: rgba(0,0,0,0.5);
            color: white;
            padding: 2rem;
            border-radius: 3px;
        }
        .game-info {
            background-color: #f5f5f5;
            border: 1px solid #ddd;
            border-radius: 3px;
            padding: 1.5rem;
            margin-bottom: 2rem;
        }
        .game-description {
            margin-bottom: 1rem;
            line-height: 1.6;
            text-align: center;
        }
        .game-features {
            display: flex;
            flex-wrap: wrap;
            gap: 1.5rem;
            margin-top: 2rem;
        }
        .feature-card {
            flex: 1 1 300px;
            background-color: white;
            border: 1px solid #ddd;
            border-radius: 3px;
            padding: 1rem;
            box-shadow: 0 1px 3px rgba(0,0,0,0.1);
        }
        .download-section {
            background-color: #f5f5f5;
            border: 1px solid #ddd;
            border-radius: 3px;
            padding: 1.5rem;
            margin-bottom: 2rem;
            text-align: center;
        }
        .download-btn {
            display: inline-block;
            background-color: #28a745;
            color: white;
            padding: 0.75rem 1.5rem;
            border-radius: 3px;
            text-decoration: none;
            margin-top: 1rem;
            font-size: 1.2rem;
            transition: background-color 0.3s;
        }
        .download-btn:hover {
            background-color: #218838;
        }
        .discord-section {
            background-color: #f5f5f5;
            border: 1px solid #ddd;
            border-radius: 3px;
            padding: 1.5rem;
            margin-bottom: 2rem;
            text-align: center;
        }
        .discord-btn {
            display: inline-block;
            background-color: #5865f2;
            color: white;
            padding: 0.75rem 1.5rem;
            border-radius: 3px;
            text-decoration: none;
            margin-top: 0.5rem;
            font-size: 1.2rem;
            transition: background-color 0.3s;
        }
        .discord-btn:hover {
            background-color: #4e5acf;
        }
        .discord-small {
            font-size: 0.9rem;
            color: #666;
            margin-top: 0.3rem;
        }
        .qq-group-section {
            background-color: #f5f5f5;
            border: 1px solid #ddd;
            border-radius: 3px;
            padding: 1.5rem;
            margin-bottom: 2rem;
            text-align: center;
        }
        .qq-group-btn {
            display: inline-block;
            background-color: #12b7f5;
            color: white;
            padding: 0.75rem 1.5rem;
            border-radius: 3px;
            text-decoration: none;
            margin-top: 0.5rem;
            font-size: 1.2rem;
            transition: background-color 0.3s;
        }
        .qq-group-btn:hover {
            background-color: #0ea5d6;
        }
        .qq-group-tip {
            font-size: 0.9rem;
            color: #666;
            margin-top: 0.8rem;
        }
        .screenshots {
            margin-top: 2rem;
            text-align: center;
        }
        .screenshot-grid {
            display: flex;
            flex-wrap: wrap;
            gap: 1rem;
            justify-content: center;
            margin-top: 1rem;
            padding: 2rem;
            background-color: #f9f9f9;
            border: 1px solid #ddd;
            border-radius: 3px;
        }
        .footer {
            background-color: #24292e;
            color: white;
            padding: 1rem;
            text-align: center;
            margin-top: 2rem;
            border-radius: 3px;
        }
    </style>
</head>
<body>
    <div class="header">
        <select class="lang-selector" id="lang-selector">
            <option value="zh">中文</option>
            <option value="en">English</option>
            <option value="ja">日本語</option>
            <option value="ko">한국어</option>
            <option value="es">Español</option>
        </select>
        <h1 id="title">OQCRP 官方前旗县角色扮演 - 官网</h1>
    </div>
    <div class="container">
        <div class="banner">
            <div class="banner-text">
                <h2 id="banner-title">欢迎来到官方前旗县角色扮演官网</h2>
                <p id="banner-desc">全部由国人创作的角色扮演游戏，在Discord</p>
            </div>
        </div>

        <div class="game-info">
            <img src="https://images.weserv.nl/?url=https://i.ibb.co/8LCgLLNF/1-A0280358-AD85-BC3226-D889705177614.jpg" style="max-width:100%;">
            <p class="game-description" id="game-desc">
                在RP游戏内，请严格遵守RP规则，否则你会获得strike，想游玩此RP，请年满13岁，否则你会被kick（踢出服务器）
            </p>
            
            <div class="game-features">
                <div class="feature-card">
                    <h3 id="feature1-title">车辆注册制</h3>
                    <p id="feature1-desc">只能开自己注册车辆，如果租车只能开你租的车辆，否则你会获得strike</p>
                </div>
                <div class="feature-card">
                    <h3 id="feature2-title">极现实的游戏</h3>
                    <p id="feature2-desc">遵守交通规则，不FRP（做出不现实的事情，但不包括staff）</p>
                </div>
                <div class="feature-card">
                    <h3 id="feature3-title">可以开公司</h3>
                    <p id="feature3-desc">可以自己开很多公司，让玩家加入你的公司，并劳动然后给工资</p>
                </div>
                <div class="feature-card">
                    <h3 id="feature4-title">紧急服务</h3>
                    <p id="feature4-desc">可以申请当医生，消防员，警察（请等警察上线）</p>
                </div>
            </div>
        </div>

        <div class="download-section">
            <h2 id="download-title">立即加入游戏</h2>
            <p id="download-desc">点击下方按钮，前往 Roblox 平台体验前旗县公服</p>
            <a href="https://www.roblox.com/share?code=17e31c3c9b40cc478c81e025115c761a&type=ExperienceDetails&stamp=1761922394972" class="download-btn" id="download-btn" target="_blank">
                立即加入游戏
            </a>
        </div>

        <div class="discord-section">
            <h2 id="discord-title">加入 OQCRP 社区</h2>
            <p class="discord-small" id="discord-desc">点击下方按钮打开 Discord 并进入 OQCRP</p>
            <a href="https://discord.gg/gAhJwuqThf" class="discord-btn" id="discord-btn" target="_blank">
                加入 Discord 社区
            </a>
        </div>

        <div class="qq-group-section">
            <h2 id="qq-title">📱 官方QQ交流群</h2>
            <p id="qq-desc">扫码或点击链接加入，获取最新游戏资讯和专属福利</p>
            <a href="https://qm.qq.com/q/pncyw1Mwhi" class="qq-group-btn" id="qq-btn" target="_blank">
                点击加入QQ群
            </a>
            <p class="qq-group-tip" id="qq-tip">群链接长期有效，若无法打开可复制链接到QQ内打开</p>
        </div>

        <div class="screenshots">
            <h2 id="screenshot-title">游戏截图</h2>
            <div class="screenshot-grid">
                <p id="screenshot-desc">更多游戏精彩截图即将上线，敬请期待！</p>
            </div>
        </div>
    </div>

    <div class="footer">
        <p id="footer">© 2025 OQCRP 官方前旗县角色扮演 版权所有</p>
    </div>

    <script>
        const langSelector = document.getElementById('lang-selector');
        let currentLang = 'zh';

        // 五大语言文本映射（中、英、日、韩、西）
        const translations = {
            // 标题
            title: {
                zh: "OQCRP 官方前旗县角色扮演 - 官网",
                en: "OQCRP Official Qianqi County Roleplay - Official Website",
                ja: "OQCRP 公式前旗県ロールプレイ - 公式サイト",
                ko: "OQCRP 공식 전기현 롤플레이 - 공식 웹사이트",
                es: "OQCRP Oficial Qianqi County Roleplay - Sitio Web Oficial"
            },
            // Banner
            bannerTitle: {
                zh: "欢迎来到官方前旗县角色扮演官网",
                en: "Welcome to the Official Qianqi County Roleplay Official Website",
                ja: "公式前旗県ロールプレイ公式サイトへようこそ",
                ko: "공식 전기현 롤플레이 공식 웹사이트에 오신 것을 환영합니다",
                es: "Bienvenido al Sitio Web Oficial de Qianqi County Roleplay"
            },
            bannerDesc: {
                zh: "全部由国人创作的角色扮演游戏，在Discord",
                en: "A roleplay game created entirely by Chinese developers, on Discord",
                ja: "中国人開発者によって完全に作成されたロールプレイゲームで、Discordでご利用いただけます",
                ko: "중국 개발자들이 전적으로 제작한 롤플레이 게임으로, Discord에서 이용하실 수 있습니다",
                es: "Un juego de rol creado completamente por desarrolladores chinos, en Discord"
            },
            // 游戏描述
            gameDesc: {
                zh: "在RP游戏内，请严格遵守RP规则，否则你会获得strike，想游玩此RP，请年满13岁，否则你会被kick（踢出服务器）",
                en: "In the RP game, please strictly follow the RP rules, otherwise you will get a strike. To play this RP, you must be at least 13 years old, otherwise you will be kicked out of the server.",
                ja: "RPゲーム内では、RPのルールを厳守してください。そうでない場合、ストライクが付与されます。このRPをプレイするには、13歳以上である必要があります。そうでない場合、サーバーからキックされます。",
                ko: "RP 게임 내에서는 RP 규칙을 엄격히 준수해 주십시오. 그렇지 않으면 스트라이크가 부여됩니다. 이 RP를 플레이하려면 13세 이상이어야 하며, 그렇지 않으면 서버에서 킬당(추방)됩니다.",
                es: "En el juego de rol, por favor siga estrictamente las reglas de RP, de lo contrario recibirá un strike. Para jugar a este RP, debe tener al menos 13 años, de lo contrario será expulsado del servidor."
            },
            // 功能卡片1：车辆注册制
            feature1Title: {
                zh: "车辆注册制",
                en: "Vehicle Registration System",
                ja: "車両登録制度",
                ko: "차량 등록 제도",
                es: "Sistema de Registro de Vehículos"
            },
            feature1Desc: {
                zh: "只能开自己注册车辆，如果租车只能开你租的车辆，否则你会获得strike",
                en: "You can only drive your own registered vehicles. If you rent a car, you can only drive the vehicle you rented, otherwise you will get a strike.",
                ja: "自分で登録した車両しか運転できません。レンタカーの場合は、レンタルした車両しか運転できません。そうでない場合、ストライクが付与されます。",
                ko: "자신이 등록한 차량만 운전할 수 있습니다. 렌트카의 경우, 렌트한 차량만 운전할 수 있으며, 그렇지 않으면 스트라이크가 부여됩니다.",
                es: "Solo puede conducir sus propios vehículos registrados. Si alquila un coche, solo puede conducir el vehículo alquilado, de lo contrario recibirá un strike."
            },
            // 功能卡片2：极现实的游戏
            feature2Title: {
                zh: "极现实的游戏",
                en: "Highly Realistic Game",
                ja: "非常にリアルなゲーム",
                ko: "매우 사실적인 게임",
                es: "Juego Altamente Realista"
            },
            feature2Desc: {
                zh: "遵守交通规则，不FRP（做出不现实的事情，但不包括staff）",
                en: "Obey traffic rules and do not FRP (do unrealistic things, except for staff).",
                ja: "交通ルールを守り、FRP（不自然な行動をすること、スタッフを除く）しないでください。",
                ko: "교통 규칙을 준수하고 FRP(부자연스러운 행동을 하는 것, 스태프 제외)하지 마십시오.",
                es: "Cumpla las reglas de tráfico y no realice FRP (hacer cosas poco realistas, excepto el personal)."
            },
            // 功能卡片3：可以开公司
            feature3Title: {
                zh: "可以开公司",
                en: "Can Start a Company",
                ja: "会社を設立できます",
                ko: "회사를 설립할 수 있습니다",
                es: "Puede Crear una Empresa"
            },
            feature3Desc: {
                zh: "可以自己开很多公司，让玩家加入你的公司，并劳动然后给工资",
                en: "You can start multiple companies, let players join your company, work and then pay them salaries.",
                ja: "複数の会社を設立し、プレイヤーにあなたの会社に加入してもらい、働いて給与を支払うことができます。",
                ko: "여러 회사를 설립하고 플레이어들에게 당신의 회사에 가입하여 일하고 임금을 지불하도록 할 수 있습니다.",
                es: "Puede crear varias empresas, permitir que los jugadores se unan a su empresa, trabajen y luego les paguen salarios."
            },
            // 功能卡片4：紧急服务
            feature4Title: {
                zh: "紧急服务",
                en: "Emergency Services",
                ja: "緊急サービス",
                ko: "긴급 서비스",
                es: "Servicios de Emergencia"
            },
            feature4Desc: {
                zh: "可以申请当医生，消防员，警察（请等警察上线）",
                en: "You can apply to be a doctor, firefighter, or police officer (please wait for the police to be online).",
                ja: "医者、消防士、警察官（警察官のオンライン待ち）に応募することができます。",
                ko: "의사, 소방관, 경찰관（경찰관 온라인 대기）으로 지원할 수 있습니다.",
                es: "Puede solicitar ser médico, bombero o policía (espera a que la policía esté en línea)."
            },
            // 下载区域
            downloadTitle: {
                zh: "立即加入游戏",
                en: "Join the Game Now",
                ja: "今すぐゲームに参加",
                ko: "지금 바로 게임에 참여",
                es: "Únete al Juego Ahora"
            },
            downloadDesc: {
                zh: "点击下方按钮，前往 Roblox 平台体验前旗县公服",
                en: "Click the button below to go to the Roblox platform and experience the Qianqi County public server.",
                ja: "以下のボタンをクリックして、Robloxプラットフォームにアクセスし、前旗県のパブリックサーバーを体験してください。",
                ko: "아래 버튼을 클릭하여 Roblox 플랫폼으로 이동하고 전기현 퍼블릭 서버를 체험해 보세요.",
                es: "Haga clic en el botón de abajo para ir a la plataforma Roblox y experimentar el servidor público de Qianqi County."
            },
            downloadBtn: {
                zh: "立即加入游戏",
                en: "Join Game Now",
                ja: "今すぐゲームに参加",
                ko: "지금 바로 게임에 참여",
                es: "Únete al Juego Ahora"
            },
            // Discord 区域
            discordTitle: {
                zh: "加入 OQCRP 社区",
                en: "Join the OQCRP Community",
                ja: "OQCRP コミュニティに参加",
                ko: "OQCRP 커뮤니티에 가입",
                es: "Únete a la Comunidad OQCRP"
            },
            discordDesc: {
                zh: "点击下方按钮打开 Discord 并进入 OQCRP",
                en: "Click the button below to open Discord and join OQCRP.",
                ja: "以下のボタンをクリックしてDiscordを開き、OQCRPに参加してください。",
                ko: "아래 버튼을 클릭하여 Discord를 열고 OQCRP에 가입하세요.",
                es: "Haga clic en el botón de abajo para abrir Discord y unirse a OQCRP."
            },
            discordBtn: {
                zh: "加入 Discord 社区",
                en: "Join Discord Community",
                ja: "Discordコミュニティに参加",
                ko: "Discord 커뮤니티에 가입",
                es: "Únete a la Comunidad de Discord"
            },
            // QQ 区域
            qqTitle: {
                zh: "📱 官方QQ交流群",
                en: "📱 Official QQ Group",
                ja: "📱 公式QQグループ",
                ko: "📱 공식 QQ 그룹",
                es: "📱 Grupo Oficial de QQ"
            },
            qqDesc: {
                zh: "扫码或点击链接加入，获取最新游戏资讯和专属福利",
                en: "Scan the code or click the link to join, get the latest game information and exclusive benefits.",
                ja: "QRコードをスキャンするかリンクをクリックして参加し、最新のゲーム情報と限定特典を入手してください。",
                ko: "QR 코드를 스캔하거나 링크를 클릭하여 가입하고 최신 게임 정보와 독점 혜택을 받으세요.",
                es: "Escanee el código QR o haga clic en el enlace para unirse, obtenga la información del juego más reciente y beneficios exclusivos."
            },
            qqBtn: {
                zh: "点击加入QQ群",
                en: "Join QQ Group Now",
                ja: "今すぐQQグループに参加",
                ko: "지금 바로 QQ 그룹에 가입",
                es: "Únete al Grupo de QQ Ahora"
            },
            qqTip: {
                zh: "群链接长期有效，若无法打开可复制链接到QQ内打开",
                en: "The group link is valid for a long time. If it cannot be opened, you can copy the link and open it in QQ.",
                ja: "グループリンクは長期有効です。開けない場合はリンクをコピーしてQQで開いてください。",
                ko: "그룹 링크는 장기간 유효합니다. 열리지 않는 경우 링크를 복사하여 QQ에서 열어주세요.",
                es: "El enlace del grupo es válido por mucho tiempo. Si no se puede abrir, puede copiar el enlace y abrirlo en QQ."
            },
            // 截图区域
            screenshotTitle: {
                zh: "游戏截图",
                en: "Game Screenshots",
                ja: "ゲームスクリーンショット",
                ko: "게임 스크린샷",
                es: "Capturas de Pantalla del Juego"
            },
            screenshotDesc: {
                zh: "更多游戏精彩截图即将上线，敬请期待！",
                en: "More exciting game screenshots will be online soon, stay tuned!",
                ja: "よりエキサイティングなゲームスクリーンショットが近日公開されますので、お楽しみに！",
                ko: "더욱 흥미로운 게임 스크린샷이 곧 공개될 예정이니, 기대해주세요!",
                es: "Más capturas de pantalla emocionantes del juego estarán disponibles pronto, estad atentos."
            },
            // 页脚
            footer: {
                zh: "© 2025 OQCRP 官方前旗县角色扮演 版权所有",
                en: "© 2025 OQCRP Official Qianqi County Roleplay. All rights reserved.",
                ja: "© 2025 OQCRP 公式前旗県ロールプレイ 著作権所有",
                ko: "© 2025 OQCRP 공식 전기현 롤플레이. 모든 권리 보유.",
                es: "© 2025 OQCRP Oficial Qianqi County Roleplay. Todos los derechos reservados."
            }
        };

        // 切换语言函数
        function switchLanguage(lang) {
            currentLang = lang;

            // 更新标题
            document.getElementById('title').textContent = translations.title[lang];
            // 更新 Banner
            document.getElementById('banner-title').textContent = translations.bannerTitle[lang];
            document.getElementById('banner-desc').textContent = translations.bannerDesc[lang];
            // 更新游戏描述
            document.getElementById('game-desc').textContent = translations.gameDesc[lang];
            // 更新功能卡片
            document.getElementById('feature1-title').textContent = translations.feature1Title[lang];
            document.getElementById('feature1-desc').textContent = translations.feature1Desc[lang];
            document.getElementById('feature2-title').textContent = translations.feature2Title[lang];
            document.getElementById('feature2-desc').textContent = translations.feature2Desc[lang];
            document.getElementById('feature3-title').textContent = translations.feature3Title[lang];
            document.getElementById('feature3-desc').textContent = translations.feature3Desc[lang];
            document.getElementById('feature4-title').textContent = translations.feature4Title[lang];
            document.getElementById('feature4-desc').textContent = translations.feature4Desc[lang];
            // 更新下载区域
            document.getElementById('download-title').textContent = translations.downloadTitle[lang];
            document.getElementById('download-desc').textContent = translations.downloadDesc[lang];
            document.getElementById('download-btn').textContent = translations.downloadBtn[lang];
            // 更新 Discord 区域
            document.getElementById('discord-title').textContent = translations.discordTitle[lang];
            document.getElementById('discord-desc').textContent = translations.discordDesc[lang];
            document.getElementById('discord-btn').textContent = translations.discordBtn[lang];
            // 更新 QQ 区域
            document.getElementById('qq-title').textContent = translations.qqTitle[lang];
            document.getElementById('qq-desc').textContent = translations.qqDesc[lang];
            document.getElementById('qq-btn').textContent = translations.qqBtn[lang];
            document.getElementById('qq-tip').textContent = translations.qqTip[lang];
            // 更新截图区域
            document.getElementById('screenshot-title').textContent = translations.screenshotTitle[lang];
            document.getElementById('screenshot-desc').textContent = translations.screenshotDesc[lang];
            // 更新页脚
            document.getElementById('footer').textContent = translations.footer[lang];
        }

        // 绑定下拉选择事件
        langSelector.addEventListener('change', function() {
            switchLanguage(this.value);
        });

        // 页面加载时初始化语言
        switchLanguage(currentLang);
    </script>
</body>
</html>
