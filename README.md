# v0.6.8

## small fixes to edit

### reference edit toggle

Reference.jsx

Orientation.jsx

Prefix.jsx

```js
import { useState } from 'react'

const Reference = ({...}) =>{

    const [isEdit, setIsEdit] = useState(false)

      return(
        <div className="content-center">
          {isEdit ? (<>) : (<>)}

        </div>

      <footer className="actions">
          <button
            className="btn edit-btn"
            onClick={() => {
              setIsEdit(!isEdit)
            }}
          >  {isEdit ? 'reference' : ' Edit'}
          </button>
      )

}
```
#   v e r s i o n 6 _ t e s t i n g  
 