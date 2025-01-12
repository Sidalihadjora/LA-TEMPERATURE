<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Soin de base : (Les constante)</title>
    <style>
        /* إعدادات الخط */
        @import url('https://fonts.googleapis.com/css2?family=Amiri&display=swap');
        body {
            font-family: 'Amiri', serif;
            background-color: #f9f9f9;
            margin: 0;
            padding: 0;
            line-height: 1.6;
        }
    
        /* عنوان الصفحة */
        body h1 {
            color: #007BFF; /* أزرق طبي */
            text-align: center;
            padding: 15px;
            font-size: 1em;
            margin: 0;
        }
    
        /* إعدادات القسم */
        section {
            width: 95%;
            max-width: 1200px;
            margin: 20px auto;
            background-color: #fff;
            box-shadow: 0px 4px 10px rgba(0, 0, 0, 0.1);
            border-radius: 10px;
            overflow: hidden;
            padding: 15px;
        }
    
        /* ألوان العناوين */
        section h2 {
            color: #0056b3; /* أزرق غامق */
            margin-bottom: 8px;
            font-size: 1.8em;
            text-align: left;
        }
    
        section h3 {
            color: #17a2b8; /* فيروزي */
            margin-bottom: 6px;
            font-size: 1.5em;
            text-align: left;
        }
    
        section h4 {
            color: #6f42c1; /* بنفسجي */
            margin-bottom: 5px;
            font-size: 1.3em;
            text-align: left;
        }
    
        section p, section ul {
            margin: 8px 15px;
            color: #333;
            font-size: 1.1em;
            text-align: left; /* توجيه النصوص لليسار */
        }
    
        section span {
            font-weight: bold;
            color: #007BFF;
        }
        /* إعدادات القائمة */
        section ul {
            list-style: disc inside;
            padding-left: 10px; /* لإبعاد القائمة قليلاً عن الحافة اليسرى */
            direction: ltr; /* جعل القائمة تتبع اتجاه النصوص الإنجليزية */
        }
    
        section ul li {
            margin-left: 10px; /* لإظهار العناصر أقرب إلى اليسار */
            text-align: left;
        }
        /* إعدادات الجدول */
        table {
            width: 100%;
            border-collapse: collapse;
            margin: 20px 0;
            text-align: left; /* توجيه محتوى الجدول لليسار */
            direction: ltr; /* الجدول بالكامل يتبع النصوص الإنجليزية */
            border-radius: 8px; /* زوايا مستديرة */
            overflow: hidden;
            box-shadow: 0px 4px 8px rgba(0, 0, 0, 0.1); /* ظل خفيف للجدول */
        }
    
        table th, table td {
            padding: 12px 15px; /* زيادة الحشو لجعل النصوص أكثر اتساعًا */
            text-align: left; /* توجيه النص داخل الجدول */
        }
    
        table th {
            background-color: #007BFF; /* خلفية زرقاء للعناوين */
            color: #fff; /* نص أبيض */
            font-weight: bold;
            text-transform: uppercase; /* تحويل النصوص إلى أحرف كبيرة */
            text-align: center;
        }
    
        table td {
            background-color: #f8f9fa; /* خلفية رمادية فاتحة للصفوف */
            color: #333; /* نص داكن */
            text-align: center;
        }
    
        /* تأثير التمرير على الصفوف */
        table tr:hover td {
            background-color: #e9f7ff; /* لون أزرق فاتح عند تمرير الفأرة */
            transition: background-color 0.3s ease; /* تأثير انتقال ناعم */
        }
    
        /* فصل الخطوط بين الصفوف */
        table tr {
            border-bottom: 1px solid #ddd;
        }
    
        /* إزالة الحد الأخير */
        table tr:last-child {
            border-bottom: none;
        }
    
        /* خطوط أفقية للعناوين */
        table th {
            border-bottom: 2px solid #0056b3; /* خط أزرق داكن للفصل بين العناوين */
        }
    
        /* استجابة الجوال */
        @media (max-width: 768px) {
            body h1 {
                font-size: 1em;
            }
    
            section {
                width: 90%;
                padding: 10px;
            }
    
            section h2 {
                font-size: 1.5em;
                margin-bottom: 6px;
            }
    
            section h3 {
                font-size: 1.2em;
                margin-bottom: 5px;
            }
    
            section h4 {
                font-size: 1.1em;
                margin-bottom: 4px;
            }
    
            section p, section ul {
                font-size: 1em;
                margin: 6px 10px;
                text-align: left;
            }
    
            section ul {
                padding-left: 8px; /* تقليل المسافة على الهواتف */
            }
    
            section ul li {
                margin-left: 8px;
            }
    
            table {
                font-size: 0.85em;
                text-align: center;
            }
    
            table th, table td {
                padding: 4px;
            }
        }
    </style>
</head>
<body>
    <h1>SOIN DE BASE</h1>
    <h1>Infirmier de santé publique 1ère année</h1>
    <h1>LES PARAMETRES VITAUX</h1>
    <h1>&copy ZERARI Sidali</h1>
    <section>
        <h2>I. LA TEMPERATURE:</h2>
        <h3>I.1 Définition</h3>
        <p>La température est le degré de chaleur du corps humain.
           Elle est variable d’un organe à l’autre à l’intérieur de l’organisme
           Plus les organes sont au milieu de l’organisme, plus la température est haute,
           il existe une répartition de la chaleur de l’intérieur vers l’extérieur.
        </p>
        <h3>I.2  Les variations de la température:</h3>
        <p>
            La température est régulée par l’hypothalamus grâce à la thermorégulation qui
            comprend la thermolyse et la thermogenèse.
        </p>
        <h4>I.2.1 Les variations physiologiques:</h4>
        <table border="2px">
            <th></th>
            <th>Température basse</th>
            <th>Température haute</th>
            <tr>
                <td>Climat</td>
                <td>Climat froid</td>
                <td>Climat chaud</td>
            </tr>
            <tr>
                <td>Digestion</td>
                <td>Diète</td>
                <td>Digestion</td>
            </tr>
            <tr>
                <td>Activité</td>
                <td>Repos et sommeil</td>
                <td>Activité physique</td>
            </tr>
            <tr>
                <td>Cycle circadien</td>
                <td>Nuit et matin : 4h – 8h</td>
                <td>Après-midi : 16h – 20h</td>
            </tr>
            <tr>
                <td>Age</td>
                <td>Personne âgée</td>
                <td>Nouveau-né</td>
            </tr>
            <tr>
                <td>Sexe</td>
                <td>/</td>
                <td>Femme : ovulation, grossesse</td>
            </tr>
        </table>
        <h4>I.2.2 Les variations pathologiques:</h4>
        <p>
            <span>Les hypothermies :</span> Une hypothermie est caractérisée par une température 
            inférieure à 35°. C’est une urgence.  Il existe deux causes à l’hypothermie :
        </p>
        <ul>
            <li><span>Les centres de la thermorégulation fonctionnent mais sont dépassés</span></li>
            <ul>
                <li>Exposition prolongée au froid extérieure, Vasoconstriction cutanée.</li>
                <li>Tachycardie.</li>
                <li>Claquement des dents.</li>
                <li>Augmentation de la tension.</li>
            </ul>
            <li><span>Les centres de la thermorégulation ne fonctionnent plus : </span></li>
            <ul>
                <li>Maladie infectieuse, septicémie.</li>
                <li>produit anesthésique, empoisonnement par les drogues.</li>
            </ul>
        </ul>
        <p>
            <span>Les hyperthermies :</span>   elle est caractérisée par une température supérieure à
            38°.
        </p>
        <li><span>Les centres de la thermorégulation fonctionnent mais sont dépassés :</span>
            exposition prolongée au chaud, activité musculaire excessive.
        </li>
        <li><span>Disfonctionnement des centres de la thermorégulation :</span> fièvre.</li>
        <h3>I.3 La prise de température:</h3>
        <h4>I.3.1 Règles générales:</h4>
        <ul>
            <li>La température doit être prise à heures régulières, deux fois par jour.</li>
            <li>La personne doit être au repos depuis 20 min avant la prise de température.</li>
        </ul>
        <h4>I.3.2 Les méthodes:</h4>
        <ul>
            <li><span>Température au passage des gros vaisseaux</span></li>
            <ul>
                <li>Se prend aux plis de flexion : creux axillaire (aisselle), creux poplité
                    (genoux), creux de l’aine (cuisse).</li>
                <li>Tamponner le pli de flexion pour enlever la sueur puis placer 
                    le thermomètre et fermer le pli.</li>
                <li>Laisser 10 minutes.</li>
                <li>Ajouter 7/10ème de degré à la température relevée.</li>
            </ul>
            <li><span>Température buccale</span></li>
            <ul>
                <li>Thermomètre réservé à cet usage à placer sous la langue.</li>
                <li>Laisser 5 minutes.</li>
                <li>Ajouter 2/10ème de degré à la température relevée.</li>
            </ul>
            <li><span>Température tympanique</span></li>
            <ul>
                <li>Thermomètre électronique à infrarouges.</li>
                <li>Le conduit auditif doit être propre, pas de cérumen ou d'écoulement.</li>
                <li>Mettre une protection couvre-sonde  à usage unique sur l'extrémité
                    de la sonde à infrarouges.</li>
                <li>Placer l'extrémité de la sonde dans le conduit auditif en dirigeant
                    la sonde vers le bas du canal.</li>
                <li>S'assurer de l'étanchéité (pas de passage d'air) entre la sonde
                    et le conduit auditif.</li>
                <li>Appuyer sur le bouton afin de déclencher la mesure.</li>
                <li>Retirer la sonde lors du signal sonore.</li>
                <li>Jeter et changer la protection couvre-sonde à chaque utilisation.</li>
            </ul>
        </ul>
        <h4>I.3.3 Précautions à prendre:</h4>
        <ul>
            <li>Nettoyer le thermomètre après chaque utilisation : eau froide
                savonneuse, alcool, désinfectant.</li>
            <li>Avant l’emploi, vérifier que le thermomètre soit sec.</li>
            <li>Evaluer le degré d’autonomie de la personne.</li>
            <li>Se laver les mains avant et après la mesure.</li>
            <li>Transmettre et inscrire sur la feuille de surveillance le résultat de la 
                mesure.</li>
        </ul>
    </section>
</body>
</html>
