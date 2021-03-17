# first-template

# Models

## InvoiceForm
```ts
export interface InvoiceForm {
    lastname: string;
    firstname: string;
    adress: string;
    params: FormParams[]
}
```

## FormParams
```ts
export interface FormParams {
    name: string;
    value: string;
}
```