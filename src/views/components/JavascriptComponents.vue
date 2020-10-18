<template>
    <section class="section section-components">
        <div class="container pb-150">
            <!-- Images -->
            <h2 class="pt-150 mb-5 align-center">
                <span>Meet our team</span>
            </h2>
            <div class="lead mt-4 mb-5">KX Transport Refrigeration has over 60 years of absolute shortest timeånumerous technicians on hand to do the job right, and in an emergency, we come to you and make sure you don’t los d to do the job right, and in an emergency, we come to you and make sure you don’t lose any time, money or cargo due to refrigeration failure.</div>
            <images></images>
            <images></images>
        </div>
    </section>
</template>
<script>
import Tabs from "@/components/Tabs/Tabs.vue";
import TabPane from "@/components/Tabs/TabPane.vue";
import Modals from "./JavascriptComponents/Modals";
const Tooltips = () => import("./JavascriptComponents/Tooltips");
const DatePickers = () => import("./JavascriptComponents/DatePickers");
import Images from "./JavascriptComponents/Images";
import TabsSection from "./JavascriptComponents/TabsSection";
import ProgressSection from "./JavascriptComponents/ProgressPagination";
import Typography from "./JavascriptComponents/Typography";

export default {
  components: {
    DatePickers,
    Images,
    Modals,
    TabPane,
    Tabs,
    TabsSection,
    ProgressSection,
    Typography,
    Tooltips
  }
};
</script>
<style>

.align-center {
    display: flex;
    width: 100%;
    justify-content: center;
}
</style>
