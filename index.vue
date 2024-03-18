<!-- <!DOCTYPE html> -->
<!-- <html lang="en">
<head>
    <meta charset="UTF-8">
     <meta name="viewport" content="width=device-width, initial-scale=1.0"> -->
    <!-- <title>Document</title> -->
    <!-- <link rel="stylesheet" href="main.css"> -->
<!-- </head> -->

<!-- <body>
    <main>
        <h1>Никита Михайлов</h1>
        <h2>Создатель профессии «Верстальщик» на Hexlet</h2>
      
        <hr>
      
        <section>
          <h2>Ключевые навыки:</h2>
          <ul>
            <li>HTML</li>
            <li>CSS</li>
            <li>JavaScript</li>
          </ul>
        </section>
      
        <section>
          <h2>О преподавателе</h2>
          <p>
            Много лет работал в аутсорсинговой компании. Развивал клиентские проекты,
            делал фичи для разных CMS. В основном верстал, готов передать весь опыт
            вам. Поработав с сотнями проектов, научился выкручиваться даже из самых
            безнадежных ситуаций. Поможет освоить верстку, чтобы она перестала
            казаться чем-то страшным.
          </p>
        </section>
      </main>
</body> -->
<!-- </html> -->
1.<template>
  <body>
    <main>
        <h1>Никита Михайлов</h1>
        <h2>Создатель профессии «Верстальщик» на Hexlet</h2>
      
        <hr>
      
        <section>
          <h2>Ключевые навыки:</h2>
          <ul>
            <li>HTML</li>
            <li>CSS</li>
            <li>JavaScript</li>
          </ul>
        </section>
      
        <section>
          <h2>О преподавателе</h2>
          <p>
            я бы сделала как положено, но у мне не дает завести чистый html, так что на vue. Отображает то же самое
          </p>
        </section>
      </main>
</body>
</template>

<script>

export default {
  name: 'indexQ',

}
</script>

<style scoped>
body {
    font-family: sans-serif;
    line-height: 1.5;
  
    background-color: #f9f9f9;
    color: #333333;
  
    width: 980px;
    margin: 0 auto;
  }
  
  h1 {
    text-align: center;
    font-size: 36px;
    margin-bottom: 0;
  }
  
  main > h2 {
    text-align: center;
    font-size: 25px;
  }
</style>
