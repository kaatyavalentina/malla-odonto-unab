# malla-odonto-unab
[Uploading malla_inte
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Malla Interactiva Odontología UNAB</title>
  <style>
    body {
      font-family: 'Segoe UI', sans-serif;
      background-color: #fff0f5;
      margin: 0;
      padding: 20px;
      overflow-x: auto;
    }
    h1 {
      text-align: center;
      color: #c2185b;
    }
    .grid {
      display: flex;
      flex-direction: row;
      gap: 15px;
      align-items: flex-start;
    }
    .semester {
      background-color: #fce4ec;
      border-radius: 10px;
      padding: 10px;
      min-width: 240px;
    }
    .semester h2 {
      text-align: center;
      font-size: 16px;
      color: #880e4f;
      margin-bottom: 10px;
    }
    .course {
      background-color: #f8bbd0;
      border-radius: 5px;
      padding: 6px;
      margin-bottom: 5px;
      cursor: pointer;
      transition: background-color 0.3s ease;
      position: relative;
    }
    .course:hover {
      background-color: #f48fb1;
    }
    .course.done {
      text-decoration: line-through;
      background-color: #d1c4e9;
    }
    .course.annual {
      border-left: 4px solid #ba68c8;
    }
    .tooltip {
      font-size: 12px;
      color: #4a148c;
    }
  </style>
</head>
<body>
  <h1>Malla Interactiva Odontología UNAB</h1>
  <div class="grid" id="malla">
    <div class="semester"><h2>Sem I</h2><div class="course">Anatomía Humana Normal y Embriología</div><div class="course">Biología Celular</div><div class="course">Física Aplicada</div><div class="course">Introducción a la Odontología</div><div class="course">Habilidades Comunicativas</div></div><div class="semester"><h2>Sem II</h2><div class="course">Anatomía Aplicada<div class="tooltip">Requiere: Anatomía Humana Normal y Embriología, Biología Celular</div></div><div class="course">Química General e Inorgánica</div><div class="course">Genética Molecular Humana<div class="tooltip">Requiere: Biología Celular</div></div><div class="course">Histología General<div class="tooltip">Requiere: Anatomía Humana Normal y Embriología, Biología Celular</div></div><div class="course">Introducción a la Clínica<div class="tooltip">Requiere: Introducción a la Odontología</div></div><div class="course">Inglés I</div></div><div class="semester"><h2>Sem III</h2><div class="course">Bioquímica General<div class="tooltip">Requiere: Química General e Inorgánica, Biología Celular</div></div><div class="course">Microbiología General<div class="tooltip">Requiere: Genética Molecular Humana</div></div><div class="course">Patología General I<div class="tooltip">Requiere: Genética Molecular Humana, Histología General, Anatomía Aplicada</div></div><div class="course">Histología Oral<div class="tooltip">Requiere: Anatomía Aplicada, Histología General</div></div><div class="course">Fisiología<div class="tooltip">Requiere: Anatomía Aplicada, Histología General</div></div><div class="course">Lab. Fisiología<div class="tooltip">Requiere: Anatomía Aplicada, Histología General</div></div><div class="course">Inglés II<div class="tooltip">Requiere: Inglés I</div></div><div class="course annual">Biomateriales Dentales<div class="tooltip">Requiere: Física Aplicada, Anatomía Aplicada, Química General e Inorgánica</div></div></div><div class="semester"><h2>Sem IV</h2><div class="course">Bioquímica Oral<div class="tooltip">Requiere: Bioquímica General, Histología Oral</div></div><div class="course">Microbiología Oral<div class="tooltip">Requiere: Bioquímica General, Microbiología General</div></div><div class="course">Patología General II<div class="tooltip">Requiere: Patología General I, Fisiología, Lab. Fisiología</div></div><div class="course">Promoción y Educación en Salud<div class="tooltip">Requiere: Introducción a la Clínica</div></div><div class="course">Razonamiento Científico y TIC</div><div class="course">Inglés III<div class="tooltip">Requiere: Inglés II</div></div></div><div class="semester"><h2>Sem V</h2><div class="course">Farmacología I<div class="tooltip">Requiere: Bioquímica Oral, Patología General II</div></div><div class="course">Inglés IV<div class="tooltip">Requiere: Inglés III</div></div><div class="course annual">Patología Dentomaxilar<div class="tooltip">Requiere: Patología General II, Microbiología Oral</div></div><div class="course annual">Imageneología<div class="tooltip">Requiere: Patología General II</div></div><div class="course annual">Cirugía Bucal Básica<div class="tooltip">Requiere: Patología General II, Microbiología Oral</div></div><div class="course annual">Fisiología Oral y Oclusión<div class="tooltip">Requiere: Biomateriales Dentales</div></div><div class="course annual">Preclínico Integrado<div class="tooltip">Requiere: Biomateriales Dentales</div></div></div><div class="semester"><h2>Sem VI</h2><div class="course">Farmacología II<div class="tooltip">Requiere: Farmacología I</div></div><div class="course">Cariología<div class="tooltip">Requiere: Microbiología Oral, Farmacología I, Inglés IV, Promoción y Educación en Salud</div></div></div><div class="semester"><h2>Sem VII</h2><div class="course">Salud Pública I<div class="tooltip">Requiere: Cariología</div></div><div class="course">Pensamiento Crítico<div class="tooltip">Requiere: Razonamiento Científico y TIC</div></div><div class="course annual">Cirugía Dentomaxilar<div class="tooltip">Requiere: Farmacología II, Patología Dentomaxilar, Imageneología, Cirugía Bucal Básica</div></div><div class="course annual">Odontología Restauradora<div class="tooltip">Requiere: Imageneología, Cirugía Bucal Básica, Preclínico Integrado, Cariología</div></div><div class="course annual">Prótesis Dentomaxilar<div class="tooltip">Requiere: Imageneología, Cirugía Bucal Básica, Fisiología Oral y Oclusión, Preclínico Integrado</div></div><div class="course annual">Endodoncia<div class="tooltip">Requiere: Farmacología II, Cariología, Patología Dentomaxilar, Imageneología, Cirugía Bucal Básica, Preclínico Integrado</div></div><div class="course annual">Periodoncia Clínica<div class="tooltip">Requiere: Farmacología II, Patología Dentomaxilar, Imageneología, Cirugía Bucal Básica, Preclínico Integrado</div></div><div class="course">Patología Maxilofacial<div class="tooltip">Requiere: Patología Dentomaxilar, Imageneología</div></div></div><div class="semester"><h2>Sem VIII</h2><div class="course">Salud Pública II<div class="tooltip">Requiere: Salud Pública I, Patología Dentomaxilar</div></div></div><div class="semester"><h2>Sem IX</h2><div class="course">Metodología de la Investigación<div class="tooltip">Requiere: Salud Pública II, Odontología Restauradora</div></div><div class="course">Medicina Oral<div class="tooltip">Requiere: Patología Maxilofacial</div></div><div class="course">Ética en la Práctica Odontológica<div class="tooltip">Requiere: Salud Pública II</div></div><div class="course annual">Cirugía y Traumatología Maxilofacial<div class="tooltip">Requiere: Cirugía Dentomaxilar, Patología Maxilofacial</div></div><div class="course annual">Clínica Integral del Adulto y Odontogeriatría<div class="tooltip">Requiere: Odontología Restauradora, Prótesis Dentomaxilar, Endodoncia, Periodoncia Clínica</div></div><div class="course annual">Odontopediatría<div class="tooltip">Requiere: Cirugía Dentomaxilar, Odontología Restauradora, Endodoncia</div></div><div class="course annual">Ortodoncia y Ortopedia Dentomaxilar<div class="tooltip">Requiere: Periodoncia Clínica</div></div></div><div class="semester"><h2>Sem X</h2><div class="course">Administración y Gestión en Salud<div class="tooltip">Requiere: Salud Pública II, Medicina Oral</div></div><div class="course">Medicina Legal<div class="tooltip">Requiere: Medicina Oral</div></div><div class="course">Responsabilidad Social</div></div><div class="semester"><h2>Sem XI-XII</h2><div class="course annual">Internado Clínico<div class="tooltip">Requiere: Cirugía y Traumatología Maxilofacial, Clínica Integral del Adulto y Odontogeriatría, Odontopediatría, Ortodoncia y Ortopedia Dentomaxilar, Ética en la Práctica Odontológica, Administración y Gestión en Salud, Medicina Legal, Responsabilidad Social</div></div><div class="course annual">Proyecto Integrado de Investigación<div class="tooltip">Requiere: Cirugía y Traumatología Maxilofacial, Clínica Integral del Adulto y Odontogeriatría, Odontopediatría, Ortodoncia y Ortopedia Dentomaxilar, Ética en la Práctica Odontológica, Administración y Gestión en Salud, Medicina Legal, Responsabilidad Social</div></div></div>
  </div>
  <script>
    document.querySelectorAll('.course').forEach(el => {
      el.addEventListener('click', () => {
        el.classList.toggle('done');
      });
    });
  </script>
</body>
</html>
ractiva_odonto_unab_completa.html…]()
