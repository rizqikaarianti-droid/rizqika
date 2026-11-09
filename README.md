<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Biodata Pribadi - Rizqika Karisti Arianti</title>
    <style>
        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }

        body {
            background-color: #f4f7f6;
            color: #333;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            padding: 20px;
        }

        .container {
            background-color: #ffffff;
            width: 100%;
            max-width: 650px;
            border-radius: 12px;
            box-shadow: 0 4px 15px rgba(0, 0, 0, 0.1);
            overflow: hidden;
        }

        .header {
            background: linear-gradient(135deg, #007bff, #0056b3);
            color: #ffffff;
            padding: 30px 20px;
            text-align: center;
        }

        .header h1 {
            font-size: 1.8rem;
            margin-bottom: 5px;
        }

        .header p {
            font-size: 1rem;
            opacity: 0.9;
        }

        .content {
            padding: 25px;
        }

        .section-title {
            font-size: 1.1rem;
            color: #0056b3;
            border-bottom: 2px solid #eef2f5;
            padding-bottom: 5px;
            margin-top: 15px;
            margin-bottom: 15px;
            text-transform: uppercase;
            letter-spacing: 0.5px;
        }

        .section-title:first-child {
            margin-top: 0;
        }

        table {
            width: 100%;
            border-collapse: collapse;
        }

        td {
            padding: 10px 5px;
            vertical-align: top;
            font-size: 0.95rem;
        }

        td.label {
            width: 35%;
            font-weight: 600;
            color: #555;
        }

        td.separator {
            width: 3%;
            text-align: center;
            color: #777;
        }

        td.value {
            width: 62%;
            color: #222;
        }

        .wa-button {
            display: inline-block;
            background-color: #25d366;
            color: white;
            padding: 6px 12px;
            border-radius: 6px;
            text-decoration: none;
            font-weight: 600;
            font-size: 0.85rem;
            margin-top: 2px;
            transition: background 0.2s ease;
        }

        .wa-button:hover {
            background-color: #1ebc57;
        }

        .footer {
            text-align: center;
            padding: 15px;
            background-color: #f9fbfd;
            font-size: 0.85rem;
            color: #777;
            border-top: 1px solid #edf2f7;
        }

        @media (max-width: 480px) {
            td.label, td.value {
                display: block;
                width: 100%;
            }
            td.separator {
                display: none;
            }
            td.label {
                padding-bottom: 2px;
            }
            td.value {
                padding-top: 0;
                margin-bottom: 10px;
            }
        }
    </style>
</head>
<body>

    <div class="container">
        <div class="header">
            <h1>Rizqika Karisti Arianti</h1>
            <p>Mahasiswi Teknologi Rekayasa Perangkat Lunak (TRPL)</p>
        </div>

        <div class="content">
            <div class="section-title">Data Diri</div>
            <table>
                <tr>
                    <td class="label">Nama Lengkap</td>
                    <td class="separator">:</td>
                    <td class="value">Rizqika Karisti Arianti</td>
                </tr>
                <tr>
                    <td class="label">Tempat, Tanggal Lahir</td>
                    <td class="separator">:</td>
                    <td class="value">Pacitan, 11 Januari 2008</td>
                </tr>
                <tr>
                    <td class="label">Jenis Kelamin</td>
                    <td class="separator">:</td>
                    <td class="value">Perempuan</td>
                </tr>
                <tr>
                    <td class="label">Agama</td>
                    <td class="separator">:</td>
                    <td class="value">Islam</td>
                </tr>
                <tr>
                    <td class="label">Kewarganegaraan</td>
                    <td class="separator">:</td>
                    <td class="value">Indonesia</td>
                </tr>
                <tr>
                    <td class="label">WhatsApp</td>
                    <td class="separator">:</td>
                    <td class="value">
                        082139672727<br>
                        <a href="https://wa.me/6282139672727" target="_blank" class="wa-button">Hubungi via WhatsApp</a>
                    </td>
                </tr>
            </table>

            <div class="section-title">Pendidikan</div>
            <table>
                <tr>
                    <td class="label">Pendidikan Terakhir</td>
                    <td class="separator">:</td>
                    <td class="value">SMKN 1 Donorojo</td>
                </tr>
                <tr>
                    <td class="label">Pendidikan Saat Ini</td>
                    <td class="separator">:</td>
                    <td class="value">Politeknik Indonusa Surakarta</td>
                </tr>
                <tr>
                    <td class="label">Program Studi</td>
                    <td class="separator">:</td>
                    <td class="value">Teknologi Rekayasa Perangkat Lunak (TRPL)</td>
                </tr>
            </table>

            <div class="section-title">Pengalaman Kerja</div>
            <table>
                <tr>
                    <td class="label">Praktik Kerja Lapangan</td>
                    <td class="separator">:</td>
                    <td class="value">
                        <strong>Uti Unik Collection and Modiste</strong><br>
                        Durasi: 6 Bulan (6 Juli 2025 – 15 Desember 2025)
                    </td>
                </tr>
            </table>
        </div>

        <div class="footer">
            &copy; Biodata Pribadi - Rizqika Karisti Arianti
        </div>
    </div>

</body>
</html>
