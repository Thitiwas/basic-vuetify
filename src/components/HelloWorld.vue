<template>
  <div class="hello">
    <div class="container">
      <div class="box">
        <h1>1</h1>
      </div>
      <div class="box">
        <h1>2</h1>
      </div>
      <div class="box">
        <h1>3</h1>
      </div>
      <div class="box">
        <h1>4</h1>
      </div>
      <div class="box">
        <h1>5</h1>
      </div>
      <div class="box">
        <h1>6</h1>
      </div>
      <div class="box">
        <h1>7</h1>
      </div>
      <div class="box">
        <h1>8</h1>
      </div>
      <div class="box">
        <h1>9</h1>
      </div>
      <div class="box">
        <h1>10</h1>
      </div>
      <div class="box">
        <h1>11</h1>
      </div>
      <div class="box">
        <h1>12</h1>
      </div>
      <div class="box">
        <h1>13</h1>
      </div>
      <div class="box">
        <h1>14</h1>
      </div>
      <div class="box">
        <h1>15</h1>
      </div>
      <div class="box">
        <h1>16</h1>
      </div>
      <div class="box">
        <h1>17</h1>
      </div>
      <div class="box">
        <h1>18</h1>
      </div>
      <div class="box">
        <h1>19</h1>
      </div>
      <div class="box">
        <h1>20</h1>
      </div>
      <div class="box">
        <h1>21</h1>
      </div>
      <div class="box">
        <h1>22</h1>
      </div>
      <div class="box">
        <h1>23</h1>
      </div>
      <div class="box">
        <h1>24</h1>
      </div>
      <div class="box">
        <h1>25</h1>
      </div>
      <div class="box">
        <h1>26</h1>
      </div>
      <div class="box">
        <h1>27</h1>
      </div>
      <div class="box">
        <h1>28</h1>
      </div>
      <div class="box">
        <h1>29</h1>
      </div>
      <div class="box">
        <h1>30</h1>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.container {
  counter-reset: box;
  display: flex;
  flex-wrap: wrap;
  max-width: auto;
  margin: 0 auto;
  border: 2px solid #000000;
}
.box {
  height: 100px;
  flex: 1 1 auto;
}
/* อิฐหมายเลข 1, 4, 8, ... */
.box:nth-child(4n + 1) {
  width: 50px;
  background-color: #48cfad;
}

/* อิฐหมายเลข 2, 6, 10, ... */
.box:nth-child(4n + 2) {
  width: 200px;
  background-color: #4fc1e9;
}

/* อิฐหมายเลข 3, 7, 11, ... */
.box:nth-child(4n + 3) {
  width: 150px;
  background-color: #ed5565;
}

/* อิฐหมายเลข 4, 8, 12, ... */
.box:nth-child(4n + 4) {
  width: 100px;
  background-color: #ac92ec;
}
h1 {
  margin: 40px 0 0;
  color: white;
}
</style>
