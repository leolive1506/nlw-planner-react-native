# Composicao de componente
```tsx
function Input() {

}

function Field() {

}

Input.Field = Field

export { Input }
```

# Create enum 
```tsx
enum StepForm {
  TRIP_DETAILS = 1,
  ADD_EMAIL = 2
}

export default function Index() {
  const [stepForm, setStepForm] = useState(StepForm.TRIP_DETAILS)
}
```