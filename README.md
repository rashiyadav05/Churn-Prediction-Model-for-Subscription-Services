# Churn-Prediction-Model-for-Subscription-Services
import { Card, CardContent, CardHeader, CardTitle } from "/components/ui/card"

export default function ChurnPredictionPage() {
  return (
    <div className="bg-white min-h-screen p-8">
      <Card className="max-w-4xl mx-auto">
        <CardHeader>
          <CardTitle className="text-3xl font-bold text-black">
            Churn Prediction Model for Subscription Services
          </CardTitle>
          <div className="border-b border-black w-full my-4" />
        </CardHeader>
        <CardContent className="space-y-6">
          <div>
            <h2 className="text-xl font-bold text-black mb-2">DESCRIPTION:</h2>
            <p className="text-black">
              This churn prediction model is designed to identify subscribers who are likely to cancel their subscriptions. By analyzing historical data and user behavior, the model provides actionable insights to reduce churn rates and improve customer retention. It can be applied across various subscription-based industries, including streaming services, SaaS platforms, and membership programs.
            </p>
          </div>
          <div>
            <h2 className="text-xl font-bold text-black mb-2">Technologies Should Used:</h2>
            <ul className="space-y-4">
              <li>
                <span className="font-bold text-black">Classification Models:</span>{" "}
                <span className="text-black">Logistic Regression, Random Forest, Gradient Boosting for predicting churn likelihood.</span>
              </li>
              <li>
                <span className="font-bold text-black">Feature Engineering:</span>{" "}
                <span className="text-black">Techniques like one-hot encoding, scaling, and feature selection to prepare data for modeling.</span>
              </li>
              <li>
                <span className="font-bold text-black">Evaluation Metrics:</span>{" "}
                <span className="text-black">Accuracy, Precision, Recall, F1-Score, and ROC-AUC to assess model performance.</span>
              </li>
              <li>
                <span className="font-bold text-black">Visualization Tools:</span>{" "}
                <span className="text-black">Matplotlib, Seaborn, and Plotly for visualizing data distributions, feature importance, and model results.</span>
              </li>
            </ul>
          </div>
        </CardContent>
      </Card>
    </div>
  )
}
