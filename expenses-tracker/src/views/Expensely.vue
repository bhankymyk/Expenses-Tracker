<template>
    <div class="container">
        <div class="row">
            <div class="col head">
                <h2>Expense Tracker</h2>
            </div>
        </div>

        <div class="row">
            <div class="col">
                <YourBalance/>
            </div>
        </div>

        <div class="row">
            <div class="col">
                <ExpensesIncome/>
            </div>
        </div>

        <div class="row">
            <div class="col">
                <History/>
            </div>
        </div>

        <div class="row">
            <div class="col">
                <AddTransaction/>
            </div>
        </div>


    </div>
</template>

<script>
import YourBalance from '@/components/YourBalance.vue';
import ExpensesIncome from '@/components/ExpensesIncome.vue';
import History from '@/components/History.vue';
import AddTransaction from '@/components/AddTransaction.vue';

    export default {
        components :{
            YourBalance,
            ExpensesIncome,
            History,
            AddTransaction
        }
        
    }
</script>

<style scoped>
.head h2{
    text-align: center;
    color: #198754;
}

</style>