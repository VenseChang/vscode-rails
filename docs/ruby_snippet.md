# Ruby Snippet v0.4.0


|Prefix||
|---|---|
|only|only: [:id]|
|except|except: [:id]|
## Route
|Prefix||
|---|---|
|get|get "/$1", to: "$2"|
|post|post "/$1", to: "$2"|
|patch|patch "/$1", to: "$2"|
|put|put "/$1", to: "$2"|
|delete|delete "/$1", to: "$2"|
|res|resources :res_name|
|res_block|resources :res_name do<br>  <br>end|
|res_collection_block|resources :res_name do<br>&nbsp;&nbsp;collection do<br>&nbsp;&nbsp;&nbsp;&nbsp;<br>&nbsp;&nbsp;end<br>end|
|res_member_block|resources :res_name do<br>&nbsp;&nbsp;member do<br><br>&nbsp;&nbsp;end<br>end|
|re|resource :res_name|
|re_block|resource :res_name do<br>  <br>end|
|re_collection_block|resource :res_name do<br>&nbsp;&nbsp;collection do<br>&nbsp;&nbsp;&nbsp;&nbsp;<br>&nbsp;&nbsp;end<br>end|
|re_member_block|resource :res_name do<br>&nbsp;&nbsp;member do<br><br>&nbsp;&nbsp;end<br>end|
|member_block|member do<br><br>end<br>|
|collection_block|collection do<br><br>end|


## Redirect
|Prefix||
|---|---|
|render|render path|
|redirect_to|redirect_to path|
|redirect_to_msg|redirect_to path, notice: "msg"|

## Model
|Prefix|shortcut||
|---|---|---|
|***relationship***|||
|has_one||has_one :|
|dependent||dependent: :id|
|has_one_dependent||has_one :id, dependent: :type|
|has_many||has_many :|
|has_many_through||has_many :model1, through: :model2|
|has_many_dependent||has_many :id, dependent: :type|
|belongs_to||belongs_to :|
|belongs_to_cache||belongs_to :id, cache: true|
|has_and_belongs_to_many|habtm|has_and_belongs_to_many :id|
|***column***|||
|t.binary|tcbi|t.binary :|
|t.boolean|tcb|t.boolean :|
|t.date|tcda|t.date :|
|t.datetime|tcdt|t.datetime :|
|t.decimal|tcd|t.decimal :|
|t.float|tcf|t.float :|
|t.integer|tci|t.integer :|
|t.references|tcr|t.references :|
|t.string|tcs|t.string :|
|t.text|tct|t.text :|
|t.time|tcti|t.time :|
|t.timestamp|tcts|t.timestamp :|
|t.timestamps|tctss|t.timestamps|
|validates||validates :column, presence: true|
|add_column||add_column :table, :column, :type|
|add_reference||add_reference :table, :column, foreign_key: true|
|**Feature**|||

## Params
|Prefix||
|---|---|
|params|params.require(:id_name).permit(:variable)|
|require|require(:id_name)|
|permit|permit(:id_name)|

## Controller
|Prefix|shortcut||
|---|---|---|
|controller||class Controller < ApplicationController<br> <br>end|
|index||def index<br><br>end|
|create||def create<br><br>end|
|new||def new<br><br>end|
|edit||def edit<br><br>end|
|show||def show<br><br>end|
|update||def update<br><br>end|
|destroy||def destroy<br><br>end|
|CRUD||def index<br><br>end<br><br>def new<br><br>end<br><br>def create<br><br>end<br><br>def edit<br><br>end<br><br>def update<br><br>end<br><br>def show<br><br>end<br><br>def destroy<br><br>end|
|before_action|ba|before_action :id|
## Others
|Prefix||
|---|---|
|if|if $1<br>&nbsp;&nbsp;$2<br>end|
|if else|if $1<br>&nbsp;&nbsp;$2<br>else<br>&nbsp;&nbsp;$3<br>end|
|if elsif|if $1<br>&nbsp;&nbsp;$2<br>elsif $3<br>&nbsp;&nbsp;$4<br>end|
|if elsif else|if $1<br>&nbsp;&nbsp;$2<br>elsif $3<br>&nbsp;&nbsp;$4<br>else<br>&nbsp;&nbsp;$5<br>end|
|first|first(quantity)|
|find_by|find_by(id: params[:id])|
|where|where(condition)|
|increment|increment(:id)|
|order|order(id: :desc)|
|limit|limit(quantity)|
|def|def {name}<br><br>end|