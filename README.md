<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Clash Royale - Accessible Game Guide</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        .card-hover:hover { transform: scale(1.05); transition: transform 0.3s ease; }
        .hero-bg { background: linear-gradient(135deg, #ff7e5f, #feb47b); }
        .accordion-content { max-height: 0; overflow: hidden; transition: max-height 0.3s ease; }
        .accordion.open .accordion-content { max-height: 500px; }
        @media (prefers-reduced-motion: reduce) { * { animation-duration: 0.01ms !important; } }
        .skip-link { position: absolute; top: -40px; left: 6px; background: #000; color: #fff; padding: 8px; z-index: 100; }
        .skip-link:focus { top: 6px; }
    </style>
</head>
<body class="bg-gray-100 text-gray-900">
    <a href="#main-content" class="skip-link">Skip to main content</a>
    <header class="hero-bg text-white py-12">
        <div class="container mx-auto px-4">
            <h1 class="text-4xl md:text-6xl font-bold text-center mb-4">Clash Royale</h1>
            <p class="text-lg md:text-xl text-center max-w-2xl mx-auto">A fast-paced, strategic tower defense game where heroes clash in epic battles. Master your deck, outsmart your opponents, and climb the ranks!</p>
        </div>
    </header>
    
    <nav class="bg-white shadow-lg sticky top-0 z-50" role="navigation" aria-label="Main navigation">
        <div class="container mx-auto px-4">
            <ul class="flex flex-wrap justify-center md:justify-start space-x-6 py-4">
                <li><a href="#about" class="hover:text-blue-500 transition">About</a></li>
                <li><a href="#features" class="hover:text-blue-500 transition">Features</a></li>
                <li><a href="#cards" class="hover:text-blue-500 transition">Cards</a></li>
                <li><a href="#strategies" class="hover:text-blue-500 transition">Strategies</a></li>
                <li><a href="#contact" class="hover:text-blue-500 transition">Contact</a></li>
            </ul>
        </div>
    </nav>

    <main id="main-content" class="container mx-auto px-4 py-8">
        <section id="about" class="mb-12">
            <h2 class="text-3xl font-bold mb-6" tabindex="0">About Clash Royale</h2>
            <div class="bg-white rounded-lg shadow-md p-6">
                <p class="text-lg leading-relaxed mb-4">Clash Royale is a free-to-play mobile strategy game developed by Supercell. It combines elements of collectible card games, tower defense, and real-time strategy. Players build and customize their decks from hundreds of unique cards, each representing troops, spells, or buildings, to destroy the opponent's towers.</p>
                <p class="text-lg leading-relaxed">The game features competitive multiplayer modes, clan battles, tournaments, and seasonal events. Whether you're a casual player or a pro, Clash Royale offers endless excitement with its balanced gameplay and community-driven updates.</p>
                <img src="https://storage.googleapis.com/workspace-0f70711f-8b4e-4d94-86f1-2a93ccde5887/image/66597383-9740-4757-9d6a-0fb5c0f4c423.png" alt="Vibrant game interface showing a Clash Royale battle scene with colorful cards, towers, and animated characters clashing on a dynamic battlefield with epic effects and strategic elements" class="w-full mt-6 rounded-lg" />
            </div>
        </section>

        <section id="features" class="mb-12">
            <h2 class="text-3xl font-bold mb-6" tabindex="0">Key Features</h2>
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-6">
                <article class="bg-white rounded-lg shadow-md p-6 card-hover">
                    <h3 class="text-xl font-semibold mb-3">Battle Arena</h3>
                    <p class="text-base leading-relaxed">Compete in fast-paced, 1v1 battles in various arenas with evolving terrains and obstacles. Earn rewards and climb the trophy ladder.</p>
                </article>
                <article class="bg-white rounded-lg shadow-md p-6 card-hover">
                    <h3 class="text-xl font-semibold mb-3">Collectible Cards</h3>
                    <p class="text-base leading-relaxed">Unlock over 100 unique cards through chests, purchases, or gifting. Upgrade cards with elixir to enhance their powers.</p>
                </article>
                <article class="bg-white rounded-lg shadow-md p-6 card-hover">
                    <h3 class="text-xl font-semibold mb-3">Clan Wars</h3>
                    <p class="text-base leading-relaxed">Join or create a clan to participate in clan wars, where team coordination and strategy shine in multi-player confrontations.</p>
                </article>
            </div>
            <img src="https://storage.googleapis.com/workspace-0f70711f-8b4e-4d94-86f1-2a93ccde5887/image/7c446a9d-f14d-413b-8384-b37a6a15dfcd.png" alt="Detailed view of Clash Royale's key features including battle arenas, collectible cards gallery, and clan war preparations with ellipses, graphics, and strategic game elements" class="w-full mt-6 rounded-lg" />
        </section>

        <section id="cards" class="mb-12">
            <h2 class="text-3xl font-bold mb-6" tabindex="0">Popular Cards</h2>
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-6">
                <article class="bg-white rounded-lg shadow-md p-4 card-hover">
                    <img src="https://storage.googleapis.com/workspace-0f70711f-8b4e-4d94-86f1-2a93ccde5887/image/318e9421-6e6d-4bba-890c-38b67af8ef22.png" alt="Illustrated card of Knight character in Clash Royale with armor, sword, and fierce expression on a fantasy medieval background" class="w-full rounded mb-4" />
                    <h3 class="text-lg font-semibold">Knight</h3>
                    <p class="text-sm">A sturdy tank unit that clashes with opponent's troops effectively.</p>
                    <button class="detail-btn mt-2 bg-blue-500 text-white px-4 py-2 rounded hover:bg-blue-600" data-detail="Knight is a cheap, reliable troop that deals moderate damage and survives longer than most low-cost units. Ideal for distracting enemies and setting up combos.">More Info</button>
                </article>
                <article class="bg-white rounded-lg shadow-md p-4 card-hover">
                    <img src="https://storage.googleapis.com/workspace-0f70711f-8b4e-4d94-86f1-2a93ccde5887/image/122042d4-a686-4c27-b31c-c24c009834d0.png" alt="Illustrated card of Fireball spell in Clash Royale showing fiery energy blast with orange and red flames on a dark mystical background" class="w-full rounded mb-4" />
                    <h3 class="text-lg font-semibold">Fireball</h3>
                    <p class="text-sm">A powerful spell that rains destruction on targets in an area.</p>
                    <button class="detail-btn mt-2 bg-blue-500 text-white px-4 py-2 rounded hover:bg-blue-600" data-detail="Fireball deals high splash damage, perfect for clearing clustered troops or hitting towers directly. Use wisely as it can backfire if overused!">More Info</button>
                </article>
                <article class="bg-white rounded-lg shadow-md p-4 card-hover">
                    <img src="https://storage.googleapis.com/workspace-0f70711f-8b4e-4d94-86f1-2a93ccde5887/image/0a249aa8-7736-4783-a2d3-671db21bf30a.png" alt="Illustrated card of Hog Rider in Clash Royale depicting a wild boar rider with axe and helmet charging forward on a rugged battlefield" class="w-full rounded mb-4" />
                    <h3 class="text-lg font-semibold">Hog Rider</h3>
                    <p class="text-sm">A fast, agile attacker that charges straight for the enemy's towers.</p>
                    <button class="detail-btn mt-2 bg-blue-500 text-white px-4 py-2 rounded hover:bg-blue-600" data-detail="Hog Rider targets the nearest building and charges through anything in its path, making it great for surprising opponents with sudden attacks.">More Info</button>
                </article>
                <article class="bg-white rounded-lg shadow-md p-4 card-hover">
                    <img src="https://storage.googleapis.com/workspace-0f70711f-8b4e-4d94-86f1-2a93ccde5887/image/5f4020bc-459d-432c-806b-a3538ecfe5a4.png" alt="Illustrated card of Goblin Barrel in Clash Royale showing a barrel launcher with goblins flying out on a decorative pirate-themed background" class="w-full rounded mb-4" />
                    <h3 class="text-lg font-semibold">Goblin Barrel</h3>
                    <p class="text-sm">Launches a barrel of goblins to distract and deal damage to towers.</p>
                    <button class="detail-btn mt-2 bg-blue-500 text-white px-4 py-2 rounded hover:bg-blue-600" data-detail="Upon landing, the barrel bursts to release three goblins that rush toward the enemy's tower, creating chaos and opening attack opportunities.">More Info</button>
                </article>
            </div>
        </section>

        <section id="strategies" class="mb-12">
            <h2 class="text-3xl font-bold mb-6" tabindex="0">Game Strategies</h2>
            <div class="space-y-4">
                <div class="accordion bg-white rounded-lg shadow-md">
                    <button class="accordion-toggle w-full text-left p-6 bg-gray-50 hover:bg-gray-100 transition" aria-expanded="false" aria-controls="strategy-1">Agro Push Strategy</button>
                    <div id="strategy-1" class="accordion-content p-6 pt-0">
                        <p>This strategy involves pressuring the opponent early with cheap units to force elixir usage, then countering their defenses. Build around units like Spear Goblins or Minion Horde.</p>
                    </div>
                </div>
                <div class="accordion bg-white rounded-lg shadow-md">
                    <button class="accordion-toggle w-full text-left p-6 bg-gray-50 hover:bg-gray-100 transition" aria-expanded="false" aria-controls="strategy-2">Beatdown Deck</button>
                    <div id="strategy-2" class="accordion-content p-6 pt-0">
                        <p>Focus on high-damage units to overwhelm the opponent. Cards like Lava Hound or Mortar can be central, supported by splash damage spells.</p>
                    </div>
                </div>
                <div class="accordion bg-white rounded-lg shadow-md">
                    <button class="accordion-toggle w-full text-left p-6 bg-gray-50 hover:bg-gray-100 transition" aria-expanded="false" aria-controls="strategy-3">Control Deck</button>
                    <div id="strategy-3" class="accordion-content p-6 pt-0">
                        <p>Maintain control with cycle cards and spells to punish mistakes. Use units like Elixir Collector or Dark Prince to sustain your elixir advantage.</p>
                    </div>
                </div>
            </div>
        </section>
    </main>

    <footer id="contact" class="bg-gray-800 text-white py-8">
        <div class="container mx-auto px-4">
            <h2 class="text-2xl font-bold mb-4" tabindex="0">Contact & Resources</h2>
            <p class="mb-4">Dive deeper into Clash Royale by visiting the official Supercell website or joining community forums. For accessibility inquiries, reach out to support.</p>
            <address class="not-italic">
                <strong>Official Site:</strong> <a href="https://clashroyale.com" class="underline hover:text-blue-300" target="_blank" rel="noopener">clashroyale.com</a><br>
                <strong>Email Support:</strong> <a href="mailto:support@supercell.com" class="underline hover:text-blue-300">support@supercell.com</a>
            </address>
        </div>
    </footer>

    <script>
        // Accordion functionality for strategies
        document.querySelectorAll('.accordion-toggle').forEach(btn => {
            btn.addEventListener('click', () => {
                const content = document.getElementById(btn.getAttribute('aria-controls'));
                const expanded = btn.getAttribute('aria-expanded') === 'true';
                btn.setAttribute('aria-expanded', !expanded);
                content.style.maxHeight = expanded ? '0' : content.scrollHeight + 'px';
            });
        });

        // Card detail modal (simple alert for demo; in production, use a real modal)
        document.querySelectorAll('.detail-btn').forEach(btn => {
            btn.addEventListener('click', () => {
                alert(btn.getAttribute('data-detail'));
            });
        });

        // Dark mode toggle (optional accessibility feature)
        const toggleDarkMode = () => {
            document.body.classList.toggle('dark');
            if (document.body.classList.contains('dark')) {
                document.body.classList.add('bg-gray-900', 'text-white');
                document.body.classList.remove('bg-gray-100', 'text-gray-900');
            } else {
                document.body.classList.remove('bg-gray-900', 'text-white');
                document.body.classList.add('bg-gray-100', 'text-gray-900');
            }
        };
        // For demonstration, add a button in header if needed
        // const darkBtn = document.createElement('button');
        // darkBtn.innerText = 'Toggle Dark Mode';
        // darkBtn.addEventListener('click', toggleDarkMode);
        // document.querySelector('header').appendChild(darkBtn);
    </script>
</body>
</html>
</content>
</create_file>
