<script lang="ts">
  import { TabContent, TabPane } from 'sveltestrap';
</script>

<TabContent>
  <TabPane tabId="appointments" tab="Appointments" active>
    <h2>Appointments</h2>
    <img
      alt="Alpha Flight"
      src="https://upload.wikimedia.org/wikipedia/en/4/49/Alpha_Flight_cast_picture_%28John_Byrne_era%29.gif"
    />
  </TabPane>
  <TabPane tabId="patients" tab="Patients">
    <h2>Patients</h2>
    <img
      alt="Johnny Bravo"
      src="https://upload.wikimedia.org/wikipedia/commons/thumb/b/be/Johnny_Bravo_series_logo.png/320px-Johnny_Bravo_series_logo.png"
    />
  </TabPane>
</TabContent>