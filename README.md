# Pasos

## 1er Paso: crear proyecto

ng new prueba
ng serve -o

## 2do paso: comprobar funcionamiento básico

Se prueba que todo esté funcionando bien, se borra elcontenido de app.component.html
se verifica que todo esté correcto en el navegador

## 3er paso: instalar Angular Material

ng add @angular/material

## 4to paso: reiniciar el servidor

ctrol + c
ng server

## 5to paso: creando módulo de Angular Material

ng g m common/angular-material

En la carpeta common/angular-material, se encuentra un módulo externo para importarlo en app.module.ts

## 6to paso: haciendo prueba en el template:

<!-- 
<div class="example-container">
    <mat-form-field appearance="fill">
        <mat-label>Input</mat-label>
        <input matInput>
    </mat-form-field>
    <br>
    <mat-form-field appearance="fill">
        <mat-label>Select</mat-label>
        <mat-select>
            <mat-option value="option">Option</mat-option>
        </mat-select>
    </mat-form-field>
    <br>
    <mat-form-field appearance="fill">
        <mat-label>Textarea</mat-label>
        <textarea matInput></textarea>
    </mat-form-field>
</div>
 -->

# FIN

Espero que les sirva.