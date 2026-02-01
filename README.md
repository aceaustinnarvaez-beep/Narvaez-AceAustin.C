<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Cannabis Strain Guide | Educational Resource</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background: linear-gradient(135deg, #005a00 0%, #003c00 100%);
            color: #005a00;
            line-height: 1.6;
            min-height: 100vh;
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
        }

        /* Hero/Intro Section */
        .hero {
            background: rgba(255, 255, 255, 0.95);
            border-radius: 20px;
            padding: 60px 40px;
            margin-bottom: 40px;
            text-align: center;
            box-shadow: 0 10px 40px rgba(0, 0, 0, 0.2);
            backdrop-filter: blur(10px);
        }

        .hero h1 {
            font-size: 3em;
            background: linear-gradient(135deg, #005a00 0%, #003c00 100%);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            background-clip: text;
            margin-bottom: 20px;
            font-weight: 700;
        }

        .hero .subtitle {
            font-size: 1.1em;
            color: #636e72;
            max-width: 800px;
            margin: 0 auto 30px;
            line-height: 1.8;
        }

        .disclaimer {
            font-size: 0.9em;
            color: #888;
            font-style: italic;
            margin-top: 20px;
        }

        /* Strain Cards */
        .strain-card {
            background: white;
            border-radius: 20px;
            overflow: hidden;
            margin-bottom: 40px;
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.15);
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }

        .strain-card:hover {
            transform: translateY(-10px);
            box-shadow: 0 15px 40px rgba(0, 0, 0, 0.25);
        }

        .strain-header {
           background: linear-gradient(135deg, #52a447 0%, #003c00 100%);
            color: white;
            padding: 40px;
            position: relative;
        }

        .strain-image-placeholder {
            width: 100%;
            height: 300px;
            background: linear-gradient(135deg, rgba(255,255,255,0.1) 0%, rgba(255,255,255,0.05) 100%);
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 1.2em;
            color: rgba(255, 255, 255, 0.7);
            margin-bottom: 20px;
            border-radius: 10px;
            border: 2px dashed rgba(255, 255, 255, 0.3);
        }

        .strain-card h2 {
            font-size: 2.5em;
            margin-bottom: 10px;
        }

        .strain-type {
            display: inline-block;
            background: rgba(255, 255, 255, 0.2);
            padding: 8px 20px;
            border-radius: 25px;
            font-size: 0.9em;
            font-weight: 600;
            backdrop-filter: blur(10px);
        }

        .strain-content {
            padding: 40px;
        }

        .info-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 30px;
            margin-bottom: 30px;
        }

        .info-box {
            background: #f8f9fa;
            padding: 25px;
            border-radius: 15px;
            border-left: 4px solid #52a447;
        }

        .info-box h3 {
            color: #52a447;
            font-size: 1.3em;
            margin-bottom: 15px;
            display: flex;
            align-items: center;
        }

        .info-box h3::before {
            content: "●";
            margin-right: 10px;
            font-size: 0.8em;
        }

        .info-box p, .info-box ul {
            color: #2d3436;
            font-size: 1em;
            line-height: 1.8;
        }

        .info-box ul {
            list-style: none;
            padding-left: 0;
        }

        .info-box li {
            padding: 8px 0;
            padding-left: 25px;
            position: relative;
        }

        .info-box li::before {
            content: "✓";
            position: absolute;
            left: 0;
            color: #52a447;
            font-weight: bold;
        }

        .thc-content {
            background: linear-gradient(135deg, #52a447 0%, #003c00 100%);
            color: white;
            padding: 15px 25px;
            border-radius: 10px;
            margin-bottom: 20px;
            font-weight: 600;
            text-align: center;
        }

        footer {
            text-align: center;
            padding: 40px 20px;
            color: white;
            margin-top: 60px;
        }

        footer p {
            background: rgba(255, 255, 255, 0.1);
            padding: 20px;
            border-radius: 10px;
            backdrop-filter: blur(10px);
        }

        /* Responsive Design */
        @media (max-width: 768px) {
            .hero h1 {
                font-size: 2em;
            }

            .strain-card h2 {
                font-size: 2em;
            }

            .info-grid {
                grid-template-columns: 1fr;
            }

            .hero {
                padding: 40px 20px;
            }

            .strain-header, .strain-content {
                padding: 30px 20px;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <!-- Hero/Intro Section -->
        <div class="hero">
            <h1>🥦 Cannabis Strain Guide</h1>
            <p class="subtitle">
                Welcome to your comprehensive guide to understanding different cannabis strains. Each variety offers unique characteristics, flavors, and therapeutic properties. This guide provides science-backed information to help you make understand the different types of strains. Learn about the distinct qualities of five notable strains below.
            </p>
            <p class="disclaimer">
                This information is for educational purposes only.
            </p>
        </div>

        <!-- Lemon Haze -->
        <div class="strain-card">
            <div class="strain-header">
                <div class="strain-image-placeholder">
                    <img src="Lemon-Haze-11.jpg" style="width: 100%; height: 100%; object-fit: cover; border-radius: 10px;">
                </div>
                <h2>Lemon Haze</h2>
                <span class="strain-type">Sativa-Dominant Hybrid (70/30)</span>
            </div>
            
            <div class="strain-content">
                <div class="thc-content">
                    THC Content: 17-25% | CBD: <1%
                </div>

                <div class="info-grid">
                    <div class="info-box">
                        <h3>Genetics & Background</h3>
                        <p>Created by crossing Lemon Skunk with Silver Haze, Lemon Haze won back-to-back High Times Cannabis Cups in 2008 and 2009. This award-winning strain has become a modern classic known for its energizing effects and citrus profile.</p>
                    </div>

                    <div class="info-box">
                        <h3>Primary Effects</h3>
                        <ul>
                            <li>Energizing and uplifting mental clarity</li>
                            <li>Enhanced creativity and focus</li>
                            <li>Euphoric mood elevation</li>
                            <li>Increased sociability</li>
                            <li>Mild body relaxation without sedation</li>
                        </ul>
                    </div>

                    <div class="info-box">
                        <h3>Flavor & Aroma</h3>
                        <p>Intense lemon and citrus notes dominate, reminiscent of freshly peeled lemon slices. Sweet undertones with hints of hash, earthy depth, and a citrus-floral sharpness. The flavor lingers with a sweet, tangy aftertaste.</p>
                    </div>

                    <div class="info-box">
                        <h3>Therapeutic Benefits</h3>
                        <ul>
                            <li>Depression and chronic stress relief</li>
                            <li>Anxiety management (in moderate doses)</li>
                            <li>Fatigue and low energy</li>
                            <li>Chronic pain and migraines</li>
                            <li>Loss of appetite</li>
                        </ul>
                    </div>

                    <div class="info-box">
                        <h3>Best Used For</h3>
                        <p>Daytime activities, creative projects, social gatherings, outdoor activities, and tasks requiring sustained focus and energy. Not recommended for evening use due to its stimulating effects.</p>
                    </div>

                    <div class="info-box">
                        <h3>Terpene Profile</h3>
                        <p><strong>Limonene</strong> (citrus, mood elevation), <strong>Pinene</strong> (mental clarity, focus), <strong>Terpinolene</strong> (uplifting, anti-fatigue)</p>
                    </div>
                </div>

                <p style="font-size: 0.85em; color: #888; margin-top: 20px;">
                    <em>Sources: Leafly, DNA Genetics, AllBud, Sirius Cannabis</em>
                </p>
            </div>
        </div>

        <!-- Bay 11 -->
        <div class="strain-card">
            <div class="strain-header">
                <div class="strain-image-placeholder">
                    <img src="bay-11-1.jpg" style="width: 100%; height: 100%; object-fit: cover; border-radius: 40px;">
                </div>
                <h2>Bay 11</h2>
                <span class="strain-type">Sativa-Dominant</span>
            </div>
            
            <div class="strain-content">
                <div class="thc-content">
                    THC Content: 19-24% | CBD: ~1%
                </div>

                <div class="info-grid">
                    <div class="info-box">
                        <h3>Genetics & Background</h3>
                        <p>Winner of the 2011 High Times Cannabis Cup, Bay 11 (also known as Granddaddy Bay 11) was bred by Grand Daddy Purp. Its exact genetics remain mysterious, though it's believed to descend from Appalachia. This Bay Area favorite is renowned for its balanced effects.</p>
                    </div>

                    <div class="info-box">
                        <h3>Primary Effects</h3>
                        <ul>
                            <li>Clear-headed cerebral euphoria</li>
                            <li>Energizing and motivating</li>
                            <li>Enhanced focus and concentration</li>
                            <li>Uplifting mood without anxiety</li>
                            <li>Gentle body relaxation (non-sedating)</li>
                        </ul>
                    </div>

                    <div class="info-box">
                        <h3>Flavor & Aroma</h3>
                        <p>Sweet and fruity with notes of mango, peach, and citrus. Earthy pine undertones complement the fruity profile. Some describe it as having a cookies-and-cream or Skittles-like sweetness with smooth, non-harsh smoke.</p>
                    </div>

                    <div class="info-box">
                        <h3>Therapeutic Benefits</h3>
                        <ul>
                            <li>Gastrointestinal pain and inflammation</li>
                            <li>Depression and mood disorders</li>
                            <li>Chronic stress and anxiety</li>
                            <li>ADD/ADHD (improved focus)</li>
                            <li>Appetite stimulation</li>
                            <li>Arthritis and chronic pain</li>
                        </ul>
                    </div>

                    <div class="info-box">
                        <h3>Best Used For</h3>
                        <p>Daytime productivity, creative work, social activities, physical tasks, and situations requiring sustained mental clarity. Many users report it helps with completing chores and staying motivated throughout the day.</p>
                    </div>

                    <div class="info-box">
                        <h3>Terpene Profile</h3>
                        <p><strong>Limonene</strong> (citrus, mood boost), <strong>Caryophyllene</strong> (stress relief), <strong>Myrcene</strong> (relaxation), <strong>Ocimene</strong>, <strong>Humulene</strong>, <strong>Linalool</strong></p>
                    </div>
                </div>

                <p style="font-size: 0.85em; color: #888; margin-top: 20px;">
                    <em>Sources: Leafly, AllBud, I Love Growing Marijuana, Wikileaf</em>
                </p>
            </div>
        </div>

        <!-- Wedding Cake -->
        <div class="strain-card">
            <div class="strain-header">
                <div class="strain-image-placeholder">
                    <img src="wedding-cake_jman.jpg" style="width: 100%; height: 100%; object-fit: cover; border-radius: 10px;">
                </div>
                <h2>Wedding Cake</h2>
                <span class="strain-type">Indica-Dominant Hybrid (60/40)</span>
            </div>
            
            <div class="strain-content">
                <div class="thc-content">
                    THC Content: 22-27% | CBD: <1%
                </div>

                <div class="info-grid">
                    <div class="info-box">
                        <h3>Genetics & Background</h3>
                        <p>Also known as Pink Cookies or Triangle Mints #23, Wedding Cake was created by Seed Junky Genetics by crossing Triangle Kush with Animal Mints. Named Leafly Strain of the Year in 2019, it's celebrated for its dessert-like flavor and potent effects.</p>
                    </div>

                    <div class="info-box">
                        <h3>Primary Effects</h3>
                        <ul>
                            <li>Deep physical relaxation</li>
                            <li>Euphoric mental state</li>
                            <li>Calming and stress-relieving</li>
                            <li>Initial sativa-like awareness</li>
                            <li>Pleasant body warmth and heaviness</li>
                            <li>Appetite stimulation</li>
                        </ul>
                    </div>

                    <div class="info-box">
                        <h3>Flavor & Aroma</h3>
                        <p>Sweet vanilla cake batter with creamy, sugary notes. Earthy pepper undertones with hints of spice and tangy citrus. Some detect caramel, mint, and nutty flavors. The aroma is rich with floral, herbal, and dank qualities.</p>
                    </div>

                    <div class="info-box">
                        <h3>Therapeutic Benefits</h3>
                        <ul>
                            <li>Chronic pain and muscle spasms</li>
                            <li>Insomnia and sleep disorders</li>
                            <li>Anxiety and stress (calming effect)</li>
                            <li>Depression and mood disorders</li>
                            <li>Loss of appetite</li>
                            <li>Fibromyalgia and MS symptoms</li>
                        </ul>
                    </div>

                    <div class="info-box">
                        <h3>Best Used For</h3>
                        <p>Evening relaxation, nighttime use, unwinding after work, or as a "nightcap." Great for movie nights, relaxation sessions, or preparing for sleep. May provide initial energy before settling into relaxation.</p>
                    </div>

                    <div class="info-box">
                        <h3>Terpene Profile</h3>
                        <p><strong>Beta-Caryophyllene</strong> (anti-inflammatory, pain relief), <strong>Limonene</strong> (anxiety/depression relief), <strong>Myrcene</strong> (sedation, relaxation)</p>
                    </div>
                </div>

                <p style="font-size: 0.85em; color: #888; margin-top: 20px;">
                    <em>Sources: Leafly, Pacific Stone, Cannaconnection, Sativa University</em>
                </p>
            </div>
        </div>

        <!-- Mary Jane -->
        <div class="strain-card">
            <div class="strain-header">
                <div class="strain-image-placeholder">
                    <img src="Maryjane.jpg" style="width: 100%; height: 100%; object-fit: cover; border-radius: 10px;">
                </div>
                <h2>Mary Jane</h2>
                <span class="strain-type">Balanced Hybrid / Sativa-Leaning</span>
            </div>
            
            <div class="strain-content">
                <div class="thc-content">
                    THC Content: 18-26% | CBD: <0.5%
                </div>

                <div class="info-grid">
                    <div class="info-box">
                        <h3>Genetics & Background</h3>
                        <p>Mary Jane is both a classic nickname for cannabis and a distinct cultivar with approachable, balanced effects. As a strain, it's presented as a versatile hybrid with bright citrus-pine aromas, fitting mainstream modern flower profiles.</p>
                    </div>

                    <div class="info-box">
                        <h3>Primary Effects</h3>
                        <ul>
                            <li>Uplifting cerebral rush</li>
                            <li>Happy, euphoric mental state</li>
                            <li>Balanced mind-body relaxation</li>
                            <li>Enhanced focus and creativity</li>
                            <li>Mood elevation without excessive energy</li>
                            <li>Slight sedation (for some users)</li>
                        </ul>
                    </div>

                    <div class="info-box">
                        <h3>Flavor & Aroma</h3>
                        <p>Classic earthy and woody flavors with hints of pine, spice, and citrus-herbal notes. Some phenotypes lean toward sweet fruity tones while others emphasize traditional hash-like profiles. The taste varies by cultivation.</p>
                    </div>

                    <div class="info-box">
                        <h3>Therapeutic Benefits</h3>
                        <ul>
                            <li>Mood swings and irritability</li>
                            <li>Depression and chronic stress</li>
                            <li>Chronic pain relief</li>
                            <li>Attention deficit disorders</li>
                            <li>Anxiety (low to moderate doses)</li>
                        </ul>
                    </div>

                    <div class="info-box">
                        <h3>Best Used For</h3>
                        <p>Versatile strain suitable for both daytime and evening use depending on dosage. Good for creative pursuits, social settings, or quiet relaxation. Balanced effects make it approachable for various activities.</p>
                    </div>

                    <div class="info-box">
                        <h3>Terpene Profile</h3>
                        <p>Varies by phenotype: <strong>Terpinolene</strong> (bright, cerebral) or <strong>Myrcene/Caryophyllene</strong> (relaxing, earthy). Check lab results for specific terpene dominance.</p>
                    </div>
                </div>

                <p style="font-size: 0.85em; color: #888; margin-top: 20px;">
                    <em>Sources: AllBud, JointCommerce Strain Database</em>
                </p>
            </div>
        </div>

        <!-- Maui Wowie -->
        <div class="strain-card">
            <div class="strain-header">
                <div class="strain-image-placeholder">
                    <img src="MauiWowie_1.jpg" style="width: 100%; height: 100%; object-fit: cover; border-radius: 10px;">
                </div>
                <h2>Maui Wowie</h2>
                <span class="strain-type">Sativa-Dominant (80/20)</span>
            </div>
            
            <div class="strain-content">
                <div class="thc-content">
                    THC Content: 19-28% | CBD: <1%
                </div>

                <div class="info-grid">
                    <div class="info-box">
                        <h3>Genetics & Background</h3>
                        <p>A legendary landrace-derived sativa originating from Hawaii in the 1960s. Grown in Maui's volcanic soil, Maui Wowie (also spelled Maui Waui) was one of the first high-THC strains. It gained fame in the counterculture era and remains a benchmark for tropical sativas.</p>
                    </div>

                    <div class="info-box">
                        <h3>Primary Effects</h3>
                        <ul>
                            <li>Energetic and euphoric mental lift</li>
                            <li>Enhanced creativity and motivation</li>
                            <li>Clear-headed, focused high</li>
                            <li>Uplifting without anxiety</li>
                            <li>Light body buzz (non-sedating)</li>
                            <li>Increased appetite</li>
                        </ul>
                    </div>

                    <div class="info-box">
                        <h3>Flavor & Aroma</h3>
                        <p>Tropical pineapple dominates with sweet citrus, pine, and hints of lavender. Fresh, fruity notes evoke a Hawaiian paradise. Smooth smoke with a lingering sweet aftertaste that's described as refreshing and light.</p>
                    </div>

                    <div class="info-box">
                        <h3>Therapeutic Benefits</h3>
                        <ul>
                            <li>Depression and mood elevation</li>
                            <li>Stress and anxiety relief (low doses)</li>
                            <li>Chronic fatigue and low energy</li>
                            <li>PTSD and trauma symptoms</li>
                            <li>Mild pain and headaches</li>
                            <li>Loss of appetite</li>
                        </ul>
                    </div>

                    <div class="info-box">
                        <h3>Best Used For</h3>
                        <p>Daytime activities, outdoor adventures, creative work, social gatherings, physical exercise, and situations requiring mental clarity. Perfect "wake and bake" strain for starting the day with positivity and energy.</p>
                    </div>

                    <div class="info-box">
                        <h3>Terpene Profile</h3>
                        <p><strong>Myrcene</strong> (relaxing, earthy), <strong>Limonene</strong> (citrus, mood boost), <strong>Pinene</strong> (alertness, focus), <strong>Caryophyllene</strong> (anti-inflammatory)</p>
                    </div>
                </div>

                <p style="font-size: 0.85em; color: #888; margin-top: 20px;">
                    <em>Sources: Leafly, Vivosun, Body&Mind Dispensaries, Sativa University</em>
                </p>
            </div>
        </div>

        <!-- Footer -->
        <footer>
            <p>
                <strong>Important Notice:</strong> This website provides educational information about cannabis strains. This website does not promote use of Marijuana as a recreational or medicinal use, with respect to Republic Act No. 9165.
            </p>
        </footer>
    </div>
</body>
</html>
 
