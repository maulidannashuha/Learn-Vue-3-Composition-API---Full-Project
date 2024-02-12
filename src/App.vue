<template>
  <Header />
  <div class="container">
    <Balance />
    <IncomeExpence />
    <TransactionList />
    <AddTransaction />
  </div>
</template>

<script>
  import Header from './components/Header.vue'
  import Balance from './components/Balance.vue'
  import IncomeExpence from './components/IncomeExpence.vue'
  import TransactionList from './components/TransactionList.vue'
  import AddTransaction from './components/AddTransaction.vue'

  export default{
    components: {
      Header,
      Balance,
      IncomeExpence,
      TransactionList,
      AddTransaction,
    }
  }
</script>