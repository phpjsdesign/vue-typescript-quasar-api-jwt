<template>
  <q-page>
    <q-card>
      <q-card-section>
        <div>
          <div>
            <div>Проекты</div>
            <div>Список проектов</div>
          </div>
          <div>
            <q-btn
              to="/projects/new"
              color="amber-6"
              label="Создать новый"
              rounded
              unelevated
            />
          </div>
        </div>
      </q-card-section>
      <q-separator/>
      <q-card-section>
        <ProjectTable/>
      </q-card-section>
    </q-card>
  </q-page>
</template>
<script setup>
import ProjectTable from 'components/projects/ProjectTable.vue'
</script>
