https://react-dnd.github.io/react-dnd/examples/sortable/simple
```js
import ExampleV2 from './dnd/ExampleV2';
import { DndProvider } from 'react-dnd';
import Backend from 'react-dnd-html5-backend';

function App() {

  return (
    <div className="App">
      <DndProvider backend={Backend}>
					<ExampleV2  />
				</DndProvider>
    </div>
  );
}

export default App;
```
