<template>
    <div>
      <adress1 one="用户协议"></adress1>
      <div class="time">发布日期:2016-4-12 09:35</div>
      <p>《小幸运会员注册协议》(以下简称“本协议”)是您与小幸运网站所有者（以下简称为“小幸运”）之间就小幸运网站服务等相关事宜所订立的契约，请您仔细阅读本协议，本协议即构成对双方有约束力的法律文件。 如果您访问小幸运网站或在小幸运网站购物，或以任何行为实际使用、享受小幸运网站的服务，即表示您接受了本协议，并同意受本协议各项条款的约束。如果您不同意本协议中的任何内容，您可以选择不使用本网站服务。 本协议包括协议正文及所有小幸运网站已经发布的或将来可能发布或更新的各类规则（在该等规则中小幸运网站或被简称为“小幸运”），所有规则为本协议不可分割的组成部分，与本协议正文具有同等法律效力。您应当仔细阅读本协议的正文内容及其所属各类规则。 小幸运网站有权根据需要不时地制订、修改本协议及/或各类规则，并以网站公示的方式进行公告，不再单独通知您。修订后的协议或将来可能发布或更新的各类规则一经在网站公布后，立即自动生效。如您不同意相关修订，应当立即停止使用21cake网站服务。您继续使用21cake网站服务，即表示您接受经修订的协议或规则。 
      </p>
      <p>一、 小幸运网站账户 <br>
        1、 用户在注册成为小幸运网站用户时所提供的信息应真实、完整、有效，并保证小幸运网站可以通过该等信息与用户本人进行联系。同时，用户也有义务在相关资料发生变更时及时更新注册信息。如果用户提供的注册资料不合法、不真实、不准确、不详尽的，用户需承担因此引起的相应责任及后果，并且21cake保留终止用户使用本站各项服务的权利。 
      </p>
      <p>
        2、 用户在本站进行浏览、下单购物等活动时，涉及用户真实姓名/名称、通信地址、联系电话、电子邮箱等隐私信息的，本站将予以严格保密，除非得到用户的授权或法律另有规定，本站不会向外界披露用户隐私信息。
      </p>
      <p>
        3、 在成功注册后，21cake网站会为每位用户开通一个账户，作为其使用21cake网站服务的唯一身份标识，用户应妥善保管该账户的用户名和密码，并对在其账户项下发生的所有行为负责。用户不得以任何形式转让或授权他人使用自己的21cake网站账户，否则用户应承担由此产生的全部责任，并与实际使用人承担连带责任。用户若发现任何非法使用用户账号或存在安全漏洞的情况，请立即通知本站并向公安机关报案。 
      </p>
    </div>
</template>
<script>
  import adress1 from './adress1'
  export default{
    name:'xieyi',
    components:{
      adress1: adress1
    }
  }
</script>
<style scoped>
  p{
    font-size: 1.2em;
    padding: 0 3%;
    text-align: left;
  }
  .time{
    /*display: inline-block;*/
    font-size: 1.2em;
    text-align: right;
    margin-right: 5%;
  }
  p:nth-child(3){
    text-indent: 2em;
    /*padding: 0 3%;*/
  }
</style>
