<template>
    <div>
        <div>
            <h1>สถานะการเข้าทำงาน</h1>
            <a href="#" class="previous round">&#8249;</a>
            <a href="#" class="next round">&#8250;</a>
        </div>
        <div>
            <table class="table tabel-striped">
              <thead class="thead-dark">  
                <tr>
                  <th>ลำดับ</th>
                  <th>ชื่อแผนก</th>
                  <th>จำนวน</th>
                  <th>หมายเหตุ</th>
                </tr>
              </thead>
            </table>
        </div>
    </div>

</template>

<script>
import axios from 'axios'
export default {
  data(){
    return{
      User: []
    }
  },
//   created(){
//     let PPP = '';
//     axios.get{apiURL}.then(res =>{
//       this.User = res.data
//     }).catch(error => {
//         console.log(error)
//     })
//   }
}
</script>

<style>
a {
  text-decoration: none;
  display: inline-block;
  padding: 8px 16px;
}

a:hover {
  background-color: #ddd;
  color: black;
}

.previous {
  background-color: #f1f1f1;
  color: black;
}

.next {
  background-color: #04AA6D;
  color: white;
}

.round {
  border-radius: 50%;
}
</style>